---
layout: page
title: Dela Teaches Ewe
subtitle: Interactive Vocabulary, Native Audio & Pronunciation Quizzes for the Ewe Language
permalink: /dela_teaches_ewe/
show_header: false
---

<style>
.app-hero-card {
  background: linear-gradient(135deg, var(--primary-ultra-light) 0%, #ffffff 100%);
  border: 1px solid var(--border-color);
  border-radius: var(--radius-lg);
  padding: 3rem;
  box-shadow: var(--shadow-md);
  margin-bottom: 3.5rem;
}

@media (max-width: 768px) {
  .app-hero-card {
    padding: 2rem 1.25rem;
  }
}

.app-hero-grid {
  display: grid;
  grid-template-columns: 180px 1fr;
  gap: 2.5rem;
  align-items: center;
}

@media (max-width: 768px) {
  .app-hero-grid {
    grid-template-columns: 1fr;
    text-align: center;
    gap: 1.75rem;
  }
}

.app-icon-wrapper {
  position: relative;
  width: 170px;
  height: 170px;
  margin: 0 auto;
}

.app-icon-img {
  width: 100%;
  height: 100%;
  border-radius: 36px;
  box-shadow: 0 12px 28px rgba(106, 27, 154, 0.18), 0 4px 10px rgba(0, 0, 0, 0.06);
  border: 3px solid #ffffff;
  object-fit: cover;
  transition: transform 0.3s ease;
}

.app-icon-img:hover {
  transform: scale(1.02);
}

.app-badges {
  display: flex;
  gap: 0.6rem;
  flex-wrap: wrap;
  margin-bottom: 1rem;
}

@media (max-width: 768px) {
  .app-badges {
    justify-content: center;
  }
}

.app-badge {
  background: var(--primary-light);
  color: var(--primary-color);
  font-size: 0.8rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  padding: 0.35rem 0.85rem;
  border-radius: var(--radius-full);
}

.app-badge-alt {
  background: #fef3c7;
  color: #92400e;
  font-size: 0.8rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  padding: 0.35rem 0.85rem;
  border-radius: var(--radius-full);
}

.app-title-area h2 {
  font-size: 2.2rem;
  color: var(--primary-color);
  margin-bottom: 0.5rem;
  line-height: 1.2;
}

.app-lead {
  font-size: 1.15rem;
  color: var(--text-muted);
  line-height: 1.6;
  margin-bottom: 1.5rem;
}

.app-actions {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

@media (max-width: 768px) {
  .app-actions {
    justify-content: center;
  }
}

/* Feature Grid */
.app-feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.75rem;
  margin-bottom: 4rem;
}

.app-feature-card {
  background: var(--bg-card);
  border: 1px solid var(--border-color);
  border-radius: var(--radius-md);
  padding: 2rem;
  box-shadow: var(--shadow-sm);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.app-feature-card:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow-md);
}

.app-feature-icon {
  width: 48px;
  height: 48px;
  border-radius: var(--radius-sm);
  background: var(--primary-ultra-light);
  color: var(--primary-color);
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1.25rem;
}

.app-feature-card h3 {
  font-size: 1.25rem;
  color: var(--primary-color);
  margin-bottom: 0.6rem;
}

.app-feature-card p {
  font-size: 0.975rem;
  color: var(--text-muted);
  line-height: 1.65;
  margin: 0;
}

/* Section Containers */
.app-section-header {
  text-align: center;
  max-width: 680px;
  margin: 0 auto 2.5rem;
}

.app-section-header h2 {
  font-size: 2rem;
  color: var(--primary-color);
  margin-bottom: 0.5rem;
}

.app-section-header p {
  color: var(--text-muted);
  font-size: 1.05rem;
}

/* FAQ Styles */
.faq-list {
  max-width: 860px;
  margin: 0 auto 4rem;
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
}

.faq-item {
  background: var(--bg-card);
  border: 1px solid var(--border-color);
  border-radius: var(--radius-md);
  padding: 1.75rem 2rem;
  box-shadow: var(--shadow-sm);
}

.faq-question {
  font-size: 1.15rem;
  font-weight: 700;
  color: var(--primary-color);
  margin-bottom: 0.6rem;
  display: flex;
  align-items: center;
  gap: 0.75rem;
}

.faq-answer {
  font-size: 1rem;
  color: var(--text-main);
  line-height: 1.7;
  margin: 0;
}

/* Support Box */
.support-banner {
  background: linear-gradient(135deg, var(--primary-color) 0%, var(--primary-hover) 100%);
  color: #ffffff;
  border-radius: var(--radius-lg);
  padding: 3.25rem 2.5rem;
  text-align: center;
  box-shadow: var(--shadow-lg);
  margin-bottom: 3rem;
}

.support-banner h2 {
  color: #ffffff;
  font-size: 2rem;
  margin-bottom: 0.75rem;
}

.support-banner p {
  color: #f3e8ff;
  font-size: 1.1rem;
  max-width: 640px;
  margin: 0 auto 2rem;
  line-height: 1.6;
}

.support-email-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.6rem;
  background: #ffffff;
  color: var(--primary-color);
  font-size: 1.1rem;
  font-weight: 700;
  padding: 0.85rem 2rem;
  border-radius: var(--radius-full);
  text-decoration: none;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.15);
  transition: transform 0.2s ease, background-color 0.2s ease;
}

.support-email-btn:hover {
  background: #faf5ff;
  transform: translateY(-2px);
  color: var(--primary-hover);
}

.support-meta {
  margin-top: 1.5rem;
  font-size: 0.9rem;
  color: #e9d5ff;
}

/* Quick Links Bar */
.app-footer-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.5rem 0;
  border-top: 1px solid var(--border-color);
  font-size: 0.95rem;
  color: var(--text-light);
  flex-wrap: wrap;
  gap: 1rem;
}

.app-footer-bar a {
  color: var(--primary-color);
  text-decoration: underline;
  font-weight: 600;
}

.app-footer-bar a:hover {
  color: var(--primary-hover);
}
</style>

<!-- Hero Section -->
<div class="app-hero-card">
  <div class="app-hero-grid">
    <div class="app-icon-wrapper">
      <img src="{{ '/images/app_icon.jpg' | relative_url }}" alt="Dela Teaches Ewe App Icon" class="app-icon-img">
    </div>
    <div class="app-title-area">
      <div class="app-badges">
        <span class="app-badge">Official App</span>
        <span class="app-badge-alt">All Ages (4+)</span>
        <span class="app-badge">100% Offline Ready</span>
      </div>
      <h2>Dela Teaches Ewe (DTE)</h2>
      <p class="app-lead">
        Build your comfort, pronunciation, and vocabulary in <strong>Ewe (Èʋegbe)</strong> with clear native audio, interactive flashcards, audio trivia quizzes, and spelling challenges.
      </p>
      <div class="app-actions">
        <a href="#support" class="btn btn-primary btn-lg">App Support &amp; Help</a>
        <a href="{{ '/dela_teaches_ewe/privacy/' | relative_url }}" class="btn btn-outline btn-lg">App Privacy Policy</a>
      </div>
    </div>
  </div>
</div>

<!-- Features Overview -->
<div class="app-section-header">
  <h2>Your Pocket Companion for Learning Ewe</h2>
  <p>Engineered for beginners, heritage learners, and language enthusiasts worldwide.</p>
</div>

<div class="app-feature-grid">
  <div class="app-feature-card">
    <div class="app-feature-icon">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2a3 3 0 0 0-3 3v7a3 3 0 0 0 6 0V5a3 3 0 0 0-3-3Z"></path><path d="M19 10v2a7 7 0 0 1-14 0v-2"></path><line x1="12" y1="19" x2="12" y2="22"></line></svg>
    </div>
    <h3>Native Audio Pronunciations</h3>
    <p>Every word and phrase includes audio spoken with authentic rhythm, tone, and pronunciation so you can speak with true confidence.</p>
  </div>

  <div class="app-feature-card">
    <div class="app-feature-icon">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
    </div>
    <h3>Quiz &amp; Spelling Challenges</h3>
    <p>Test your listening skills with multiple-choice audio quizzes and spelling drills that track your score and reinforce active recall.</p>
  </div>

  <div class="app-feature-card">
    <div class="app-feature-icon">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2" ry="2"></rect><line x1="8" y1="21" x2="16" y2="21"></line><line x1="12" y1="17" x2="12" y2="21"></line></svg>
    </div>
    <h3>100% Offline Capability</h3>
    <p>All flashcards and audio clips are bundled directly in the app. Practice anytime on the go without requiring cellular data or Wi-Fi.</p>
  </div>

  <div class="app-feature-card">
    <div class="app-feature-icon">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"></path><path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"></path></svg>
    </div>
    <h3>Comprehensive Vocabulary</h3>
    <p>Covers numbers 1–10, 11–20, bigger numbers, foods, days of the week, months, common everyday phrases, and the Ewe alphabet.</p>
  </div>

  <div class="app-feature-card">
    <div class="app-feature-icon">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"></rect><path d="M7 11V7a5 5 0 0 1 10 0v4"></path></svg>
    </div>
    <h3>No Account or Sign-Up Needed</h3>
    <p>We respect your privacy. No account creation, email, or login is required. Your quiz and spelling scores stay stored safely on your device.</p>
  </div>

  <div class="app-feature-card">
    <div class="app-feature-icon">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
    </div>
    <h3>Clean &amp; Accessible Design</h3>
    <p>Designed with legible typography, high-contrast palettes, and intuitive navigation so learners of all ages can focus on studying.</p>
  </div>
</div>

<!-- Support & FAQs Section -->
<div class="app-section-header" id="faqs">
  <h2>Frequently Asked Questions</h2>
  <p>Quick answers to common questions about using Dela Teaches Ewe.</p>
</div>

<div class="faq-list">
  <div class="faq-item">
    <div class="faq-question">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>
      Does the app work completely offline?
    </div>
    <p class="faq-answer">
      Yes! All audio recordings, vocabulary lists, flashcards, quizzes, and spelling challenges are packaged directly inside the app bundle. Once installed, you can study without any active internet or cellular connection.
    </p>
  </div>

  <div class="faq-item">
    <div class="faq-question">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>
      How do I report pronunciation, spelling, or translation suggestions?
    </div>
    <p class="faq-answer">
      We love feedback from native Ewe speakers and learners alike! If you have suggestions, corrections, or dialect notes, please email us directly at <a href="mailto:info@delateaches.com?subject=Dela%20Teaches%20Ewe%20Feedback">info@delateaches.com</a> with the subject line <em>"Dela Teaches Ewe Feedback"</em>.
    </p>
  </div>

  <div class="faq-item">
    <div class="faq-question">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>
      How is my learning progress and quiz scores saved?
    </div>
    <p class="faq-answer">
      Your quiz results, spelling progress, and preferences are stored directly on your physical mobile device. We do not require you to register an account, and we do not store your personal profile on external servers.
    </p>
  </div>

  <div class="faq-item">
    <div class="faq-question">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>
      Will new vocabulary categories and audio be added?
    </div>
    <p class="faq-answer">
      Yes! We are continually developing new learning sets, expanding conversational phrases, and refining audio pronunciations. App updates will deliver these additions directly through the App Store and Google Play.
    </p>
  </div>

  <div class="faq-item">
    <div class="faq-question">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>
      How can I learn English or get 1-on-1 language coaching?
    </div>
    <p class="faq-answer">
      Dela Teaches LLC also provides English fluency coaching, reading comprehension, and pronunciation instruction for adults and youth. Visit our <a href="{{ '/lessons/' | relative_url }}">Lessons &amp; Pricing</a> page or <a href="{{ '/contact/' | relative_url }}">Book a Discovery Call</a> to learn more.
    </p>
  </div>
</div>

<!-- Support Contact Section (Apple Store Support URL Target) -->
<div class="support-banner" id="support">
  <h2>Need Help or Have a Question?</h2>
  <p>
    Whether you ran into a bug, have an audio question, or want to suggest new vocabulary, our team is here to assist you.
  </p>
  <a href="mailto:info@delateaches.com?subject=Dela%20Teaches%20Ewe%20Support%20Request" class="support-email-btn">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
    Contact Support: info@delateaches.com
  </a>
  <div class="support-meta">
    Developer: <strong>Dela Teaches LLC</strong> &bull; Response Time: Typically within 24–48 hours
  </div>
</div>

<!-- Bottom Nav Links -->
<div class="app-footer-bar">
  <div>
    <strong>Dela Teaches Ewe (DTE)</strong> &bull; Bundle ID: <code>com.abelmartin.delateachesewe</code>
  </div>
  <div>
    <a href="{{ '/dela_teaches_ewe/privacy/' | relative_url }}">App Privacy Policy</a> &bull;
    <a href="{{ '/privacy/' | relative_url }}">Website Privacy</a> &bull;
    <a href="{{ '/' | relative_url }}">Dela Teaches Home</a>
  </div>
</div>
