---
layout: page
title: Contact Me
order: 4
---

<!-- modify this form HTML and place wherever you want your form -->
<!-- <form
  action="https://formspree.io/f/mjggkylk"
  method="POST"
  class="contact-form"
>
  <label>
    Your email:
    <input type="email" name="email" placeholder="email@example.com" required>
  </label>
  <label>
    Your message:
    <textarea name="message" placeholder="How can I help you?" required></textarea>
  </label>
  <button type="submit">Send</button>
</form> -->

<form action="https://formspree.io/f/mjggkylk" method="POST" class="contact-form">
  <label for="email">Your Email</label>
  <input type="email" name="email" id="email" placeholder="email@example.com" required>

  <label for="message">Your Message</label>
  <textarea name="message" id="message" placeholder="How can I help you?" required></textarea>

  <button type="submit">Send Message</button>
</form>
