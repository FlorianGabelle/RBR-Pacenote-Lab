---
layout: page
title: Documentation
lang: en
show_title: false
---

Welcome to the documentation for **RBR Pacenote Lab**, a tool for generating co-driver pacenotes in the rally simulator *Richard Burns Rally*.

Follow the steps below to create accurate, customizable, and data-driven pacenotes for any stage.

---

<section class="layout--articles">
  <div class="grid grid--p-3">
    {% assign docs = site.pages | where: "lang", "en" | where: "type", "doc" | sort: "order" %}
    {% for post in docs %}
      {% include post-card.html post=post %}
    {% endfor %}
  </div>
</section>
