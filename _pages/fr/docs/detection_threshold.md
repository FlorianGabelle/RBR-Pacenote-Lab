---
layout: article
title: "Seuil de détection"
excerpt: "Paramètres d’analyse"
show_date: false
lang: fr
type: doc
order: 100
cover: /assets/images/docs/fr/main_window/detection_threshold.png
sidebar:
  nav: docs-fr
---

Le **seuil de détection** est un paramètre clé de l’analyse. Il influence plusieurs aspects de l’interprétation des données de télémétrie :

- Détection du début du virage  
- Détection de la fin du virage  
- Calcul de la longueur des virages  
- Calcul des distances entre virages (et donc la détection des enchaînements)

{% include image.html
   src="/assets/images/docs/fr/main_window/detection_threshold.png"
   alt="Seuil de détection"
   max_width="100%" %}

---

### 🔽 Baisser le seuil

Un seuil plus bas :

- Permet de détecter les virages à **faible** amplitude (ex. : courbes rapides)
- Allonge la **durée** des virages détectés, ce qui peut parfois réduire la précision ou compliquer l'enchaînement des appels

---

### 🔼 Augmenter le seuil

Un seuil plus élevé :

- Filtre les variations mineures du volant, en **ignorant** les mouvements de faible amplitude
- Améliore la **séparation** entre les virages

---

### ✅ Paramètre recommandé

La valeur par défaut de **10 degrés** offre un **compromis équilibré**, fonctionnant bien avec les longueurs de coin, les seuils de liaison et les distances standards.

Vous pouvez ajuster ce paramètre en fonction de vos besoins spécifiques :

- **Diminuez** la valeur pour rendre la détection plus sensible, ce qui aide à identifier les virages mineurs ou rapides.

- **Augmentez** légèrement la valeur si des virages proches sont regroupés et détectés comme un seul virage.

Abaisser le seuil de détection n’entraîne pas toujours de meilleurs résultats ou des notes de meilleure qualité. Dans certains cas, un seuil plus élevé peut être plus efficace. La détection de virages de très faible intensité peut poser problème, notamment en rendant difficile la distinction entre des virages consécutifs et rapprochés.

> 📌 Remarque : les données brutes du volant sont prétraitées — elles sont sous-échantillonnées et filtrées pour réduire le bruit autour du seuil et améliorer les performances.
