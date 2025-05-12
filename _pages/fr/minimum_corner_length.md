---
layout: article
title: "Longueur minimale des virages"
excerpt: "Paramètres d’analyse"
show_date: false
lang: fr
type: doc
order: 11
# cover: /assets/images/ui/fr/pacenote_graphics_editor/default.PNG
sidebar:
  nav: docs-fr
---

Le paramètre **longueur minimale des virages** permet de filtrer les virages très courts ou non souhaités lors de l’analyse.

Ces détections brèves peuvent être dues à :

- Du bruit dans le signal
- Des mouvements de volant brusques ou involontaires

Ajuster cette valeur permet de réduire les faux positifs et d’améliorer la clarté des pacenotes.

---

### ⚙️ Configuration

- **Augmentez** la valeur pour ignorer les virages très courts ou peu significatifs  
- **Diminuez**-la si des virages serrés valides (ex. : épingles) sont ignorés

> 💡 Astuce : pour ajuster ce paramètre, zoomez sur les épingles et virages à 90° dans la vue carte. Cela permet de vérifier que les virages nets et légitimes ne sont pas filtrés par erreur.
