---
layout: article
title: "Longueur des virages"
excerpt: "Configuration"
show_date: false
lang: fr
type: doc
order: 50
cover: /assets/images/docs/fr/configuration_window/corner_lengths.png
sidebar:
  nav: docs-fr
---

L’application calcule la longueur des virages à partir des données de télémétrie.

Les longueurs sont classées selon les catégories suivantes :

- Court
- Normal (aucun appel)
- Long
- Très long

{% include image.html
   src="/assets/images/docs/fr/configuration_window/corner_lengths.png"
   alt="Longueur des virages"
   max_width="80%" %}

---

### ⚙️ Configuration

Pour chaque catégorie, vous pouvez :

- L’**activer** ou la désactiver  
- Définir son **seuil** de longueur  
- Attribuer un **appel** personnalisé

---

> 📌 Remarque : la longueur détectée d’un virage dépend du **seuil de détection du volant**.  
> Un seuil plus bas entraîne une détection plus tôt à l’entrée, et plus tard à la sortie — ce qui donne des virages plus longs.
