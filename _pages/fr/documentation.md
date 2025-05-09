---
layout: articles
title: Documentation
lang: fr
show_title: false
---

Bienvenue dans la documentation de **RBR Pacenote Lab**. Cet outil avancé permet de générer des notes de copilote pour le simulateur de rallye *Richard Burns Rally*.

En suivant les étapes décrites ci-dessous, vous pourrez produire des notes très précises et personnalisables, basées sur des données, pour n'importe quelle spéciale.

---

<section class="layout--articles">
  <div class="grid grid--p-3">
    {% assign docs = site.pages | where: "lang", "fr" | where: "type", "doc" %}
    {% for post in docs %}
      {% include post-card.html post=post %}
    {% endfor %}
  </div>
</section>

