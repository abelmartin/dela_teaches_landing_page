---
layout: default
title: Read, Speak & Grow
---

<section class="hero container">
  <div class="hero-grid">
    <div>
      <span class="hero-tag">Dela Teaches LLC</span>
      <h1 class="hero-title">Read, Speak, & <span>Grow</span></h1>
      <p class="hero-subtitle">Build your pronunciation, fluency, and reading skills so you can express yourself clearly and confidently in real conversations.</p>
      <div class="hero-actions">
        <a href="{{ '/lessons/' | relative_url }}" class="btn btn-primary btn-lg">View Lessons & Pricing</a>
        <a href="{{ '/quick-start/' | relative_url }}" class="btn btn-outline btn-lg">Get Started</a>
      </div>
    </div>
    <div class="hero-image-wrapper">
      <img src="{{ '/images/KF8e8XXkokpm9v9SCKJxYmCPi8tD4s7qOmIYIpmi.png' | relative_url }}" alt="Dela Teaches Student Coaching" class="hero-img">
    </div>
  </div>
</section>

<section class="section container">
  <div class="grid-2" style="align-items: center;">
    <div>
      <img src="{{ '/images/d026tMFJCbsj9UCqXBnoV3ULftq9uv0G2G1G35Ul.png' | relative_url }}" alt="Dela Teacher" style="border-radius: var(--radius-md); box-shadow: var(--shadow-md);">
    </div>
    <div>
      <span class="hero-tag" style="background-color: var(--primary-light);">About Dela</span>
      <h2>Hello, I'm Dela</h2>
      <p>I’m an English teacher with over 10 years of experience teaching adults and kids. I hold a Master’s in TESOL (Teaching English to Speakers of Other Languages) and have taught English in schools, community centers, and online.</p>
      <p>I love teaching and seeing my students read, speak, and grow in English with clear pronunciation and natural confidence.</p>
      <a href="{{ '/about/' | relative_url }}" class="btn btn-outline">Read Full Story &rarr;</a>
    </div>
  </div>
</section>

<section class="section container">
  <div class="section-header">
    <h2>Lessons & Coaching</h2>
    <p class="section-subtitle">Tailored English learning designed around your goals</p>
  </div>

  <div class="grid-2">
    <div class="card pricing-card">
      <div>
        <h3>Single Lesson</h3>
        <p><em>Pay as you go, one session at a time</em></p>
        <div class="price">$60</div>
        <ul class="pricing-features">
          <li>
            <svg class="w-5 h-5" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="20 6 9 17 4 12"></polyline></svg>
            1-on-1 Personalized Session
          </li>
          <li>
            <svg class="w-5 h-5" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="20 6 9 17 4 12"></polyline></svg>
            Pronunciation or Conversation focus
          </li>
          <li>
            <svg class="w-5 h-5" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="20 6 9 17 4 12"></polyline></svg>
            Tailored reading & speaking feedback
          </li>
        </ul>
      </div>
      <a href="https://tidycal.com/delamartin/single-lesson-fall25" target="_blank" rel="noopener" class="btn btn-primary w-full">Book Single Lesson</a>
    </div>

    <div class="card pricing-card featured">
      <div class="badge-featured">Best Value</div>
      <div>
        <h3>5-Lesson Bundle</h3>
        <p><em>Save $25 when you book 5 classes</em></p>
        <div class="price">$275</div>
        <ul class="pricing-features">
          <li>
            <svg class="w-5 h-5" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="20 6 9 17 4 12"></polyline></svg>
            5 Dedicated 1-on-1 Sessions
          </li>
          <li>
            <svg class="w-5 h-5" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="20 6 9 17 4 12"></polyline></svg>
            Comprehensive Pronunciation Plan
          </li>
          <li>
            <svg class="w-5 h-5" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="20 6 9 17 4 12"></polyline></svg>
            Guided Reading & Vocabulary materials
          </li>
        </ul>
      </div>
      <a href="https://tidycal.com/delamartin/5-lesson-bundle-fall25" target="_blank" rel="noopener" class="btn btn-gold w-full">Book 5-Lesson Package</a>
    </div>
  </div>
  
  <div style="text-align: center; margin-top: 2rem;">
    <a href="{{ '/lessons/' | relative_url }}" class="btn btn-outline">Explore All Lesson Options &rarr;</a>
  </div>
</section>

<section class="section container">
  <div class="section-header">
    <h2>From the Language Blog</h2>
    <p class="section-subtitle">Practical advice to boost your English reading, pronunciation, and speaking confidence.</p>
  </div>

  <div class="blog-grid">
    {% for post in site.posts limit:3 %}
      <div class="card blog-card">
        <div class="blog-card-meta">
          <span>{{ post.date | date: "%B %d, %Y" }}</span>
          <span>&bull;</span>
          <span>By {{ post.author | default: "Dela" }}</span>
        </div>
        <h3 class="blog-card-title"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        <p class="blog-card-excerpt">{{ post.excerpt | strip_html | truncatewords: 24 }}</p>
        <div class="blog-card-footer">
          <a href="{{ post.url | relative_url }}" class="btn btn-outline" style="padding: 0.4rem 1rem; font-size: 0.9rem;">Read Article &rarr;</a>
        </div>
      </div>
    {% endfor %}
  </div>

  <div style="text-align: center; margin-top: 2.5rem;">
    <a href="{{ '/blog/' | relative_url }}" class="btn btn-primary">Visit Language Blog &rarr;</a>
  </div>
</section>

<section class="container">
  <div class="newsletter-box">
    <h2>Join the Dela Teaches Newsletter</h2>
    <p>Get weekly guidance, pronunciation tips, and learning resources sent directly to your inbox.</p>
    {% include newsletter-form.html %}
  </div>
</section>
