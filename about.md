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

<section class="timeline-section">
  <h2 class="section-heading">Education</h2>
  <ol class="timeline">
    <li class="timeline-item">
      <span class="timeline-date">2026 – Present <span class="degree">MD Candidate</span></span>
      <h3>University of Michigan Medical School</h3>
      <p>Doctor of Medicine candidate</p>
    </li>
    <li class="timeline-item">
      <span class="timeline-date">2025 – 2026 <span class="degree">MS</span></span>
      <h3>Duke University, Fuqua School of Business</h3>
      <p>Master of Science in Quantitative Management, Healthcare Emphasis</p>
    </li>
    <li class="timeline-item">
      <span class="timeline-date">2022 – 2025 <span class="degree">BA</span></span>
      <h3>Northwestern University</h3>
      <p>Neuroscience, with minors in Data Science and Global Health Studies. Posse Scholar and 2024 <a href="#ubben">Jeff Ubben Posse Fellow</a>.</p>
    </li>
  </ol>
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
