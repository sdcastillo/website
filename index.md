---
layout: default
title: PredictiveAnalyst
description: The Edukate education template and Exam PA HTML viewer that make up this site.
samwiki: true
---

<div class="sw-lede">
  <div class="sw-lede-copy">
    <h2>What this site holds</h2>
    <p>This repository is the PredictiveAnalyst site. The README and the GitHub description both use that name. The files checked in are a static front end: the <a href="https://htmlcodex.com/online-education-website-template">HTML Codex Edukate</a> online-education template, a separate 404 page from the Mediplus medical template, a screenshot of the education layout, and a small viewer written to list HTML files from another repository. The tree has no model, dataset, or study notes of its own.</p>
    <p>Edukate is the shell on the home page and on About, Courses, Course Detail, Features, Instructors, Testimonials, and Contact. The home header reads “Learn From Home” and “Education Courses.” Under that is a search box with a Courses menu and a Keyword field. The page then runs through an about block, a “Why You Should Start Learning with Us?” section (Skilled Instructors, International Certificate, Online Classes), six course cards, a “30% Off For New Students” signup, an instructor carousel, student quotes, and a contact form. The nav is Home, About, Courses, a Pages menu (Course Detail, Our Features, Instructors, Testimonial), and Contact. The footer lists Web Design, Apps Design, Marketing, Research, and SEO, and it keeps the HTML Codex credit that <code>LICENSE.txt</code> requires.</p>
    <p>The words on those pages are still the template defaults. The about counters are 123 available subjects, 1234 online courses, 123 skilled instructors, and 1234 happy students. Every course card is titled “Web design &amp; development courses for beginners,” attributed to Jhon Doe, and rated 4.5 from 250 reviews. The detail page repeats that title and lists instructor John Doe, 15 lectures, 10.00 hours, skill level All Level, language English, and a price of $199. Instructors are labeled “Instructor Name” in “Web Design &amp; Development.” Testimonials are “Student Name” in “Web Design.” Contact is 123 Street, New York, USA, a 012 phone number, and info@example.com. The longer paragraphs are the template’s filler copy.</p>
    <p>Those HTML files point at <code>css/style.css</code>, <code>js/main.js</code>, <code>lib/</code> (Owl Carousel, easing, waypoints, counter-up), and <code>img/</code> for the about photo, course photos, instructor photos, and testimonial photos. Those directories were not uploaded with the pages, so the styled Edukate layout is recorded in <code>online-education-website-template.jpg</code>. The 404 file is a different HTML Codex template, Mediplus, titled “Mediplus - Free Medical and Doctor Directory HTML Template,” with its own line “Oop's sorry we can't find that page!” plus open hours and a newsletter. It uses the Mediplus stylesheet names, which are also absent from this repository.</p>
    <p><code>embed-code.md</code> is a standalone page titled “GitHub HTML Viewer.” Its script requests <code>https://api.github.com/repos/sdcastillo/ExamPAContent/contents/</code>, builds a tab for each <code>.html</code> file in that response, and loads the selected file through <code>htmlpreview.github.io</code>. That viewer is the only file here that points at Exam PA material. The original Edukate and Mediplus documents stay in <code>template/</code> so this home page can use the shared SamWiki skin while those files remain intact.</p>
  </div>
  <aside class="sw-find" aria-label="Site facts">
    <h2>Site facts</h2>
    <ul>
      <li><strong>Name</strong> PredictiveAnalyst site, from the README and the GitHub description.</li>
      <li><strong>Education template</strong> Edukate by HTML Codex. <code>LICENSE.txt</code> is CC BY 4.0 and requires the HTML Codex credit, which the footer still carries.</li>
      <li><strong>Edukate pages</strong> Home, About, Courses, Course Detail, Features, Instructors, Testimonials, and Contact.</li>
      <li><strong>Placeholder course</strong> Web design for beginners, Jhon Doe, 4.5 (250), 15 lectures, 10 hours, $199.</li>
      <li><strong>404 page</strong> Mediplus medical-directory template, stored beside the Edukate files.</li>
      <li><strong>Exam PA viewer</strong> <code>embed-code.md</code> tabs HTML from <code>sdcastillo/ExamPAContent</code> and previews it with htmlpreview.github.io.</li>
      <li><strong>Missing from the tree</strong> <code>css/</code>, <code>js/</code>, <code>lib/</code>, and <code>img/</code>. The screenshot is the record of the styled layout.</li>
    </ul>
  </aside>
</div>

<section class="sw-section" id="pages">
  <div class="sw-section-head">
    <h2>Original pages <span class="sw-pill">HTML</span></h2>
    <p>The template files are unchanged and live under <code>template/</code>. Styles and images they reference are still not in this repository. The viewer stays at the repository root as <code>embed-code.md</code>.</p>
  </div>
  <div class="sw-grid">
    <article class="sw-card">
      <div class="sw-card-top">
        <h3 class="sw-name"><a href="template/index.html">Edukate home</a></h3>
        <span class="sw-lang">HTML</span>
      </div>
      <p class="sw-desc">“Learn From Home” and “Education Courses,” with the about counters, course carousel, signup, instructors, testimonials, and contact form.</p>
      <p class="sw-meta">template/index.html</p>
      <div class="sw-actions">
        <a class="sw-btn sw-btn-live" href="template/index.html">Open page</a>
        <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/website/blob/main/template/index.html">View source</a>
      </div>
    </article>
    <article class="sw-card">
      <div class="sw-card-top">
        <h3 class="sw-name"><a href="template/detail.html">Course detail</a></h3>
        <span class="sw-lang">HTML</span>
      </div>
      <p class="sw-desc">The beginner web-design course: John Doe, 15 lectures, 10.00 hours, All Level, English, and a price of $199.</p>
      <p class="sw-meta">template/detail.html</p>
      <div class="sw-actions">
        <a class="sw-btn sw-btn-live" href="template/detail.html">Open page</a>
      </div>
    </article>
    <article class="sw-card">
      <div class="sw-card-top">
        <h3 class="sw-name"><a href="template/404.html">Mediplus 404</a></h3>
        <span class="sw-lang">HTML</span>
      </div>
      <p class="sw-badge">Other template</p>
      <p class="sw-desc">A medical-directory 404, “Oop's sorry we can't find that page!”, with open hours and a newsletter. It is not the Edukate shell.</p>
      <p class="sw-meta">template/404.html</p>
      <div class="sw-actions">
        <a class="sw-btn sw-btn-live" href="template/404.html">Open page</a>
      </div>
    </article>
    <article class="sw-card">
      <div class="sw-card-top">
        <h3 class="sw-name"><a href="online-education-website-template.jpg">Template screenshot</a></h3>
        <span class="sw-lang">JPG</span>
      </div>
      <p class="sw-desc">The styled Edukate layout. Use this when the HTML pages have no local CSS or images to load.</p>
      <p class="sw-meta">online-education-website-template.jpg</p>
      <div class="sw-actions">
        <a class="sw-btn sw-btn-live" href="online-education-website-template.jpg">Open image</a>
      </div>
    </article>
    <article class="sw-card">
      <div class="sw-card-top">
        <h3 class="sw-name"><a href="https://github.com/sdcastillo/website/blob/main/embed-code.md">GitHub HTML viewer</a></h3>
        <span class="sw-lang">HTML</span>
      </div>
      <p class="sw-desc">Tabs built from the ExamPAContent contents API, each opened through htmlpreview.github.io.</p>
      <p class="sw-meta">embed-code.md</p>
      <div class="sw-actions">
        <a class="sw-btn sw-btn-source" href="https://github.com/sdcastillo/website/blob/main/embed-code.md">View source</a>
      </div>
    </article>
  </div>
</section>

## The rest of the Edukate shell

- [About](template/about.html) repeats the “First Choice For Online Education Anywhere” counters and the three reasons to start: skilled instructors, an international certificate, and online classes.
- [Courses](template/course.html) is the six-card grid. Each card uses the same beginner web-design title.
- [Features](template/feature.html) is the “Why Choose Us?” block on its own page.
- [Instructors](template/team.html) is the four-person carousel of “Instructor Name.”
- [Testimonials](template/testimonial.html) is the pair of “Student Name” quotes.
- [Contact](template/contact.html) is the New York address, phone, email, and message form.
- [READ-ME.txt](READ-ME.txt) names the template, the HTML Codex link, and the license file.
