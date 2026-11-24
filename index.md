---
layout: default
title: Home
description: "John Saleeb is a first-year medical student at the University of Michigan interested in the physician-patient relationship and the systems and software that shape care."
---

<section class="hero-section">
  <div class="hero-text">
    <h1>Hi, I'm <br><span>John Saleeb</span></h1>
    <p>
      I'm a first-year medical student at the University of Michigan, interested in the systems that create our care experience.
      I want to understand what strains the physician-patient relationship, and how patient-facing software can ease that tension. Along the way I've worked hands-on with wearable health technology, across hardware, mechanical, and electrical engineering.
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
      <h3>Physician-Patient Relationship</h3>
      <p>Studying what strains the relationship between physicians and patients, and how patient-facing software can relieve that tension.</p>
    </div>
    
    <div class="stat-card">
      <h3>Wearables &amp; Analytics</h3>
      <p>Hands-on experience with wearable technology across mechanical and electrical engineering, plus analytics research on surgical outcomes and care delivery.</p>
    </div>
    
    <div class="stat-card">
      <h3>Ubben Posse Fellow</h3>
      <p>2024 Jeff Ubben Posse Fellow, mentored by Dr. Bryan T. Kelly, CEO of Hospital for Special Surgery. <a href="{{ '/about/#ubben' | relative_url }}">Read more</a>.</p>
    </div>
  </div>
</section>

<section class="video-wrapper">
  <h2 class="section-title">My TEDx Talk</h2>
  <p class="section-intro">
    Watch my TEDx talk where I discuss innovative approaches, ideas, and experiences in education, growth, and community.
  </p>
  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/oiXWMKi_Wec" title="John Saleeb TEDx Talk" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
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
