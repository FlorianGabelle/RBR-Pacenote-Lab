---
layout: article
title: "Enchaînements et distances"
excerpt: "Configuration"
show_date: false
lang: fr
type: doc
order: 6
cover: /assets/images/docs/fr/links_and_distances/settings.PNG
sidebar:
  nav: docs-fr
---

Cette section permet de configurer deux fonctionnalités clés :

- **Enchaînements entre virages** (ex. : *« dans »*, *« et »*)  
- **Appels de distance**

{% include image.html
   src="/assets/images/docs/fr/links_and_distances/settings.PNG"
   alt="Enchaînements et distances"
   max_width="80%" %}

---

### ⚙️ Configuration – Enchaînements entre virages

Vous pouvez activer ou désactiver les enchaînements, et ajuster le **seuil de distance** entre deux virages.  
Ce seuil détermine à partir de quelle proximité un appel d'enchaînement est déclenché (ex. : *« dans »*).

Autres options disponibles :

- Sélection de l’appel d'enchaînement (ex. : *« dans »*, *« et »*)  
- Combinaison de l’appel d'enchaînement avec l’appel précédent, pour une annonce plus rapprochée

> ⚠️ Des seuils trop faibles peuvent regrouper plusieurs virages dans les sections sinueuses, rendant les appels plus difficiles à suivre.

---

### ⚙️ Configuration – Appels de distance

Vous pouvez aussi activer un appel spécifique pour signaler une ligne droite importante :

- Activez ou désactivez la fonction  
- Définissez la **distance minimale** à partir de laquelle l’appel est déclenché

Cela permet au pilote d’anticiper une accélération prolongée ou un freinage à venir.

---

> 📌 Remarque : les distances détectées dépendent du **seuil de détection du volant**.  
> Un seuil plus bas provoque une détection plus tôt de l’entrée du virage et plus tard de la sortie — ce qui allonge la durée du virage détecté et réduit la distance calculée entre deux virages.
