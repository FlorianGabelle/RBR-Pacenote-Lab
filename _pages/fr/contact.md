---
layout: page
title: Contact
lang: fr
show_date: false
---

<div class="form-container">
  <form class="contact-form" action="https://formsubmit.co/rbr.pacenote.lab@gmail.com" method="POST">
    <!-- Protection anti-spam -->
    <input type="hidden" name="_honey" style="display:none">
    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_next" value="{{ '/fr/thank_you/' | absolute_url }}">

    <label for="name">Nom complet :</label>
    <input type="text" name="name" id="name" required>

    <label for="email">Adresse e-mail :</label>
    <input type="email" name="email" id="email" required>

    <label for="message">Message :</label>
    <textarea name="message" id="message" rows="6" required></textarea>

    <button type="submit" class="button button--primary button--pill">
        Envoyer le message
    </button>
  </form>
</div>
