---
layout: default
title: Home
description: "John Saleeb is a first-year medical student at the University of Michigan working in neuroscience, healthcare analytics, and medical devices."
---

<section class="hero-section">
  <div class="hero-text">
    <h1>Hi, I'm <br><span>John Saleeb</span></h1>
    <p>
      I'm a first-year medical student at the University of Michigan and a Northwestern neuroscience alum.
      I work where neuroscience, data science, and healthcare analytics meet, building technology-driven solutions for clinical outcomes, medical devices, and health equity.
    </p>
    <div class="hero-actions">
      <a href="{{ '/research/' | relative_url }}" class="btn btn-primary">See My Research</a>
      <a href="{{ '/about/' | relative_url }}" class="btn btn-secondary">More About Me</a>
    </div>
  </div>
  <div class="hero-image">
    <img src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="John Saleeb" loading="lazy">
  </div>
</section>

<section id="about-me" class="glance-section">
  <h2 class="section-title">At a Glance</h2>
  
  <div class="quick-stats">
    <div class="stat-card">
      <h3>Neuroscience</h3>
      <p>Majored in Neuroscience at Northwestern University, studying brain-behavior relationships and clinical neuro-technologies.</p>
    </div>
    
    <div class="stat-card">
      <h3>Healthcare Analytics</h3>
      <p>Applying analytics and data science to surgical outcomes and healthcare delivery, through research with teams at Duke and beyond.</p>
    </div>
    
    <div class="stat-card">
      <h3>Ubben Posse Fellow</h3>
      <p>2024 Jeff Ubben Posse Fellow, shadowing industry leaders like Dr. Bryan T. Kelly (CEO, Hospital for Special Surgery).</p>
    </div>
  </div>
</section>

<section class="video-wrapper">
  <h2 class="section-title">My TEDx Talk</h2>
  <p class="section-intro">
    Watch my TEDx talk where I discuss innovative approaches, ideas, and experiences in education, growth, and community.
  </p>
  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/oiXWMKi_Wec?start=83" title="John Saleeb TEDx Talk" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</section>

<section class="contact-section" id="contact">
  <h2 class="section-title">Say Hello</h2>
  <p class="section-intro">
    Whether you want to talk research, healthcare, or just catch up, my inbox is open.
  </p>
  <div class="contact-actions">
    {% if site.email %}<a href="mailto:{{ site.email }}" class="btn btn-primary">Email Me</a>{% endif %}
    {% if site.linkedin_url != "" %}<a href="{{ site.linkedin_url }}" class="btn btn-secondary" target="_blank" rel="noopener">LinkedIn</a>{% endif %}
    {% if site.cv_url != "" %}<a href="{{ site.cv_url | relative_url }}" class="btn btn-secondary" target="_blank" rel="noopener">Download CV</a>{% endif %}
  </div>
</section>
