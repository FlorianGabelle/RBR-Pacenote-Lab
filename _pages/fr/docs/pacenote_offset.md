---
layout: article
title: "Avance/retard des notes"
excerpt: "Paramètres d’analyse"
show_date: false
lang: fr
type: doc
order: 120
cover: /assets/images/docs/fr/pacenote_offset/setting.PNG
sidebar:
  nav: docs-fr
---

Le réglage **avance/retard des notes** permet d’ajuster finement la position des appels de virage sur la carte de la spéciale.

Comme le placement des notes dépend de l’algorithme de détection de virage, leur position par défaut peut ne pas correspondre à votre préférence — notamment selon le seuil de détection utilisé.

La valeur est exprimée en mètres :
- Une **valeur négative** avance la note (elle est placée plus tôt, avant le virage)
- Une **valeur positive** la retarde (elle est placée plus loin dans le virage)

{% include image.html
   src="/assets/images/docs/fr/pacenote_offset/setting.PNG"
   alt="Avance/retard des notes"
   max_width="100%" %}

---

### ⚙️ Configuration

- Si vous utilisez un **seuil de détection élevé**, l’entrée en virage est détectée tardivement, et les notes peuvent être placés trop loin dans le virage  
  → Utilisez une **valeur négative** pour les avancer

- Si vous utilisez un **seuil de détection bas**, l’entrée en virage est détectée très tôt, et les notes peuvent apparaître trop tôt  
  → Utilisez une **valeur positive** pour les retarder

---

> 🔎 Remarque : ce réglage s’applique uniquement aux notes de virage.  
> Les appels de distance restent positionnés à la fin du virage précédent et ne sont pas concernés.
