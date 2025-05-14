---
layout: article
title: "Seuil de détection"
excerpt: "Paramètres d’analyse"
show_date: false
lang: fr
type: doc
order: 10
cover: /assets/images/docs/fr/detection_threshold/setting.PNG
sidebar:
  nav: docs-fr
---

Le **seuil de détection** est un paramètre clé de l’analyse. Il influence plusieurs aspects de l’interprétation des données de télémétrie :

- Détection du début du virage  
- Détection de la fin du virage  
- Calcul de la longueur des virages  
- Calcul des distances entre virages (et donc la détection des enchaînements)

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/docs/fr/detection_threshold/setting.PNG">
      <img src="/assets/images/docs/fr/detection_threshold/setting.PNG" style="display: block; margin: 0 auto; max-width: 100%;" alt="Detection Threshold Setting" />
    </a>
  </figure>
</div>

---

### 🔽 Baisser le seuil

Un seuil plus bas :

- Permet de détecter les virages à faible amplitude (ex. : courbes rapides)
- Allonge la durée des virages détectés, ce qui peut parfois réduire la précision ou compliquer l'enchaînement des appels

---

### 🔼 Augmenter le seuil

Un seuil plus élevé :

- Filtre les variations mineures du volant, en ignorant les mouvements de faible amplitude
- Améliore la séparation entre les virages

---

### ✅ Réglage recommandé

La valeur par défaut de **10 degrés** offre un bon compromis avec les réglages standards pour la longueur des virages, les liaisons et les distances.

Selon votre usage :

- Baissez la valeur pour augmenter la sensibilité et détecter plus de virages  
- Augmentez-la légèrement pour réduire les faux positifs ou le bruit de signal

Au fur et à mesure que vous prenez en main l’outil, vous pouvez essayer de baisser le seuil pour affiner la détection.  
Cependant, cela peut nécessiter d’ajuster d’autres paramètres comme les distances et enchaînements, le filtrage des virages ou le placement des pacenotes pour conserver un bon niveau de qualité.

> 📌 Remarque : les données brutes du volant sont prétraitées — elles sont sous-échantillonnées et filtrées pour réduire le bruit autour du seuil et améliorer les performances.
