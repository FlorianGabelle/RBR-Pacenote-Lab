---
layout: page
title: Documentation
lang: fr
show_date: false
---

Bienvenue dans la documentation de **RBR Pacenote Lab**, un outil permettant de générer des pacenotes copilote pour le simulateur de rallye *Richard Burns Rally*.

Suivez les étapes ci-dessous pour créer des pacenotes précises, personnalisables et basées sur des données, pour n’importe quelle spéciale.

---

<section class="layout--articles">
  <div class="grid grid--p-3">
    {% assign docs = site.pages | where: "lang", "fr" | where: "type", "doc" | sort: "order" %}
    {% for post in docs %}
      {% include post-card.html post=post %}
    {% endfor %}
  </div>
</section>
