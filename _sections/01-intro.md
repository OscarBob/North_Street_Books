---
section_id: intro
section_class: intro-section
order: 1
---

## Welcome to The Reading Nook

A cosy independent bookshop in the heart of Bookshire, offering carefully curated collections and a warm atmosphere for book lovers.

### Opening Hours

<div class="hours-grid">
  <div class="hours-item"><strong>Monday - Wednesday:</strong> {{ site.hours.monday }}</div>
  <div class="hours-item"><strong>Thursday - Friday:</strong> {{ site.hours.thursday }}</div>
  <div class="hours-item"><strong>Saturday:</strong> {{ site.hours.saturday }}</div>
  <div class="hours-item"><strong>Sunday:</strong> {{ site.hours.sunday }}</div>
</div>

### Get in Touch

<div class="contact-info">
  <div class="contact-item">
    <strong>📧 Email:</strong> <a href="mailto:{{ site.email }}">{{ site.email }}</a>
  </div>
  <div class="contact-item">
    <strong>📞 Phone:</strong> <a href="tel:{{ site.phone }}">{{ site.phone }}</a>
  </div>
  <div class="contact-item">
    <strong>📍 Address:</strong> {{ site.address }}
  </div>
</div>

### Find Us Online

<div class="social-links">
  <a href="https://twitter.com/{{ site.social.twitter }}" target="_blank">Twitter</a>
  <a href="https://instagram.com/{{ site.social.instagram }}" target="_blank">Instagram</a>
  <a href="https://facebook.com/{{ site.social.facebook }}" target="_blank">Facebook</a>
</div>

<details class="menu-details">
  <summary class="menu-toggle">☕ See Our Café Menu</summary>
  <div class="menu-content">
    <h4>Hot Beverages</h4>
    <ul>
      <li>Coffee (Espresso, Americano, Latte) - £3.50</li>
      <li>Tea (English Breakfast, Earl Grey, Herbal) - £2.80</li>
      <li>Hot Chocolate - £3.80</li>
    </ul>
    
    <h4>Treats</h4>
    <ul>
      <li>Fresh Scones with Jam & Cream - £4.50</li>
      <li>Slice of Cake - £4.20</li>
      <li>Cookies - £2.50</li>
    </ul>
  </div>
</details>
