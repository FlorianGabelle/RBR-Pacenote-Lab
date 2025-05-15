---
layout: article
title: "Courbe du volant"
excerpt: "Visualisation"
show_date: false
lang: fr
type: doc
order: 8
cover: /assets/images/docs/fr/steering_trace/steering_view.PNG
sidebar:
  nav: docs-fr
---

La **courbe du volant** est un outil de diagnostic qui visualise votre entrée de direction pendant la reco et vous aide à comprendre comment les virages sont détectés lors de l’analyse.  
Bien qu’elle puisse paraître complexe au début — notamment si vous débutez avec la télémétrie — elle fournit des informations précieuses sur les données brutes derrière vos pacenotes.

Elle permet d’évaluer la qualité de votre conduite, de comprendre pourquoi un virage a été détecté d’une certaine façon, et d’ajuster vos paramètres d’analyse si nécessaire.

{% include image.html
   src="/assets/images/docs/fr/steering_trace/steering_view.PNG"
   alt="Courbe du volant"
   max_width="100%" %}

---

### 🟥🟦 Éléments affichés

- Les lignes rouges horizontales représentent le **seuil de détection**, défini dans les paramètres d’analyse  
- Les segments bleus indiquent les **virages détectés**

> ℹ️ Vous pouvez remarquer que les segments bleus ne commencent ou ne se terminent pas exactement lorsque la courbe croise les lignes de seuil.  
> Cela s’explique par un sous-échantillonnage des données et un passage à un **échantillonnage basé sur la distance** plutôt que sur le temps — un choix conçu pour assurer cohérence et performance, quel que soit la configuration.

> ⚙️ Astuce : utilisez la courbe du volant conjointement avec la carte de la spéciale pour affiner vos réglages de détection et valider la précision des virages.

---

### 🖱️ Contrôles souris

Les mêmes interactions que pour la carte de la spéciale s’appliquent ici :

- **Clic gauche + glisser** — déplacer la vue  
- **Molette** — zoom avant/arrière  
- **Clic droit** — réinitialiser le niveau de zoom
