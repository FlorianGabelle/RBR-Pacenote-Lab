---
layout: page
title: Contact
lang: en
show_date: false
---

{% raw %}
<div class="form-container">
  <form class="contact-form" action="https://formsubmit.co/rbr.pacenote.lab@gmail.com" method="POST">
    <!-- Spam protection -->
    <input type="hidden" name="_honey" style="display:none">
    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_next" value="http://127.0.0.1:4000/en/thank_you/">

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
{% endraw %}