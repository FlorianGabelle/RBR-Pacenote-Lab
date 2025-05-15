---
layout: page
title: Contact
lang: en
show_date: false
---

<div class="form-container">
  <form class="contact-form" action="https://formsubmit.co/rbr.pacenote.lab@gmail.com" method="POST">
    <!-- Spam protection -->
    <input type="hidden" name="_honey" style="display:none">
    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_next" value="{{ '/en/thank_you/' | absolute_url }}">

    <label for="name">Full Name:</label>
    <input type="text" name="name" id="name" required>

    <label for="email">Email Address:</label>
    <input type="email" name="email" id="email" required>

    <label for="message">Message:</label>
    <textarea name="message" id="message" rows="6" required></textarea>

    <button type="submit" class="button button--primary button--pill">
        Send Message
    </button>
  </form>
</div>
