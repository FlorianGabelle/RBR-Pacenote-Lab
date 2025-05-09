---
layout: page
title: Documentation
lang: en
show_title: false
---

Welcome to the documentation for **RBR Pacenote Lab**, an advanced tool for generating co-driver pacenotes for the rally simulator *Richard Burns Rally*.

By following the steps outlined below, you'll be able to produce highly accurate and customizable data-driven pacenotes for any stage.

---

<section class="layout--articles">
  <div class="grid grid--p-3">
    {% assign docs = site.pages | where: "lang", "en" | where: "type", "doc" %}
    {% for post in docs %}
      {% include post-card.html post=post %}
    {% endfor %}
  </div>
</section>

