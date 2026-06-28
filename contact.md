---
layout: page
title: Contact Me
order: 4
---

<h2 class="page-title">Contact Me</h2>
<p class="page-subtitle">Get in Touch</p>


<form class="contact-form reveal"
      action="https://formspree.io/f/myzkoqjr"
      method="POST">

  <div class="form-group">
    <label class="form-label" for="email">Your Email</label>
    <input class="form-control"
           type="email"
           id="email"
           name="email"
           placeholder="you@example.com"
           required />
  </div>

  <div class="form-group">
    <label class="form-label" for="message">Your Message</label>
    <textarea class="form-control"
              id="message"
              name="message"
              placeholder="How can I help you?"
              required></textarea>
  </div>

  <button type="submit" class="form-submit">Send Message</button>

</form>
