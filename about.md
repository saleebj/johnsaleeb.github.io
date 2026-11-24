---
layout: default
title: About Me
permalink: /about/
description: "About John Saleeb: medical student, the physician-patient relationship, and patient-facing technology."
---

<h1 class="page-title">About Me</h1>
<p class="page-intro">
  I'm John, a first-year medical student at the University of Michigan. I'm drawn to the systems behind our care experience: what strains the physician-patient relationship, and how patient-facing software can help.
  Here's the short version of how I got here and what I care about.
</p>

<section class="about-grid">
  <div class="about-card">
    <span class="project-tag">Education</span>
    <h3>Northwestern University</h3>
    <p>Neuroscience major, with minors in Data Science and Global Health Studies.</p>
  </div>
  <div class="about-card">
    <span class="project-tag">Now</span>
    <h3>University of Michigan</h3>
    <p>First-year medical student.</p>
  </div>
  <div class="about-card">
    <span class="project-tag">Business of Health</span>
    <h3>Duke University</h3>
    <p>Fuqua School of Business, connecting clinical research with how healthcare is built and run.</p>
  </div>
  <div class="about-card">
    <span class="project-tag">Fellowship</span>
    <h3>Jeff Ubben Posse Fellow</h3>
    <p>2024 fellow, mentored by Dr. Bryan T. Kelly, CEO of Hospital for Special Surgery. <a href="#ubben">More below</a>.</p>
  </div>
</section>

<section class="goals-section">
  <h2>What I Care About</h2>
  <ul class="goals-list">
    <li><strong>The physician-patient relationship:</strong> understanding the pressures that strain it, from time and paperwork to the systems around each visit.</li>
    <li><strong>Patient-facing software:</strong> tools that ease that tension and help patients feel heard and informed.</li>
    <li><strong>Building real things:</strong> experience with wearable technology across hardware, mechanical, and electrical engineering.</li>
  </ul>
</section>

<section class="feature-section" id="ubben">
  <div class="feature-image">
    <img src="{{ '/assets/images/ubben-fellowship.jpg' | relative_url }}" alt="John Saleeb during his 2024 Jeff Ubben Posse Fellowship" loading="lazy">
  </div>
  <div class="feature-text">
    <span class="project-tag">2024 Fellowship</span>
    <h2>Jeff Ubben Posse Fellowship</h2>
    <p>
      In summer 2024, as a Northwestern Posse Scholar, I was one of five students selected as a Jeff Ubben Posse Fellow.
      I was paired with Dr. Bryan T. Kelly, CEO of Hospital for Special Surgery, and spent the summer seeing how a leading hospital is run.
      Afterward, I interviewed Dr. Kelly about medicine, orthopedics, and leadership.
    </p>
    <div class="feature-links">
      <a href="https://www.possefoundation.org/news-and-events/ubben-posse-fellow-interviews-dr-bryan-t-kelly-md-mba" target="_blank" rel="noopener" class="btn btn-primary">Read My Interview</a>
      <a href="https://www.pr.com/press-release/917737" target="_blank" rel="noopener" class="btn btn-secondary">Fellowship Announcement</a>
    </div>
  </div>
</section>

<section class="contact-section">
  <h2 class="section-title">Let's Connect</h2>
  <p class="section-intro">Always happy to talk research, healthcare, or anything else.</p>
  <div class="contact-actions">
    {% if site.email %}<a href="mailto:{{ site.email }}" class="btn btn-primary">Email Me</a>{% endif %}
    {% if site.linkedin_url != "" %}<a href="{{ site.linkedin_url }}" class="btn btn-secondary" target="_blank" rel="noopener">LinkedIn</a>{% endif %}
  </div>
</section>
