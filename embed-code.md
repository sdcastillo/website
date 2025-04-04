
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>GitHub HTML Viewer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .tabs {
            display: flex;
            flex-wrap: wrap;
            border-bottom: 2px solid #ccc;
        }
        .tab {
            padding: 10px 15px;
            cursor: pointer;
            border: 1px solid #ccc;
            border-bottom: none;
            background-color: #f1f1f1;
            margin-right: 5px;
        }
        .tab.active {
            background-color: white;
            font-weight: bold;
        }
        .iframe-container {
            width: 100%;
            height: 600px;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>
    <h1>GitHub HTML Viewer</h1>
    <div class="tabs" id="tab-container"></div>
    <iframe id="iframe-viewer" class="iframe-container"></iframe>
    
    <script>
        const repoUrl = 'https://api.github.com/repos/sdcastillo/ExamPAContent/contents/';
        const tabContainer = document.getElementById('tab-container');
        const iframeViewer = document.getElementById('iframe-viewer');

        async function fetchHtmlFiles() {
            try {
                const response = await fetch(repoUrl);
                const data = await response.json();

                data.forEach(item => {
                    if (item.name.endsWith('.html')) {
                        const tab = document.createElement('div');
                        tab.classList.add('tab');
                        tab.textContent = item.name;
                        tab.onclick = () => openFile(item.html_url, tab);
                        tabContainer.appendChild(tab);
                    }
                });
            } catch (error) {
                console.error('Error fetching repository contents:', error);
            }
        }

        function openFile(url, tabElement) {
            // Remove active class from all tabs
            document.querySelectorAll('.tab').forEach(tab => tab.classList.remove('active'));
            tabElement.classList.add('active');
            
            // Display selected HTML file
            iframeViewer.src = `https://htmlpreview.github.io/?${url}`;
        }

        // Load HTML files on page load
        fetchHtmlFiles();
    </script>
</body>
</html>
