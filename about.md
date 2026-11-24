---
layout: default
title: About Me
permalink: /about/
description: "About John Saleeb: neuroscience, healthcare analytics, and a life outside the lab."
---

<h1 class="page-title">About Me</h1>
<p class="page-intro">
  I'm John, a first-year medical student at the University of Michigan. I like big questions about the brain and health, and I like answering them with data.
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
    <p>2024 fellow, shadowing leaders such as Dr. Bryan T. Kelly, CEO of Hospital for Special Surgery.</p>
  </div>
</section>

<section class="goals-section">
  <h2>What I Care About</h2>
  <ul class="goals-list">
    <li><strong>Better care through data:</strong> using analytics to make surgery safer and pain management smarter.</li>
    <li><strong>Technology that reaches everyone:</strong> low-cost diagnostics and wearables that work outside big hospitals.</li>
    <li><strong>Health equity:</strong> finding where the system leaves people behind, and fixing it.</li>
  </ul>
</section>

<section class="contact-section">
  <h2 class="section-title">Let's Connect</h2>
  <p class="section-intro">Always happy to talk research, healthcare, or anything else.</p>
  <div class="contact-actions">
    {% if site.email %}<a href="mailto:{{ site.email }}" class="btn btn-primary">Email Me</a>{% endif %}
    {% if site.linkedin_url != "" %}<a href="{{ site.linkedin_url }}" class="btn btn-secondary" target="_blank" rel="noopener">LinkedIn</a>{% endif %}
  </div>
</section>
