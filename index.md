---
layout: default
title: Home
description: "John Saleeb is a researcher at Northwestern & Duke University specializing in neuroscience, healthcare analytics, and medical devices."
---

<section class="hero-section">
  <div class="hero-text">
    <h1>Hi, I'm <br><span>John Saleeb</span></h1>
    <p>
      I am a researcher bridging the intersection of <strong>Neuroscience</strong>, <strong>Data Science</strong>, and <strong>Healthcare Analytics</strong>. 
      Currently pursuing my studies at Duke University's Fuqua School of Business and an alumnus of Northwestern University. I work on building technology-driven solutions for clinical outcomes, medical devices, and health equity.
    </p>
    <div class="hero-actions">
      <a href="{{ '/projects/' | relative_url }}" class="btn btn-primary">View My Projects</a>
      <a href="#about-me" class="btn btn-secondary">Learn More</a>
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
      <p>Applying advanced analytics and data science methods at Duke University to solve complex surgical and healthcare delivery challenges.</p>
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
