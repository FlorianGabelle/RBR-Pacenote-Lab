---
layout: article
title: "Problèmes connus"
excerpt: "Informations importantes"
show_date: false
lang: fr
order: 11
cover: /assets/images/warning.png
sidebar:
  nav: docs-fr
---

## ⚠️ Remarque sur la compatibilité avec Roadbook v1.6.2

**RBR Roadbook v1.6.2** devrait fonctionner correctement dans la plupart des cas, y compris pour l'import/export de fichiers de notes avec **Pacenote Lab**.

Cependant, dans de rares situations, il *pourrait* réécrire les IDs de notes de virage, ce qui pourrait entraîner une interprétation différente de l’échelle des notes.

### Que faire (par précaution)
Si vous remarquez un comportement inhabituel après l'importation de vos notes, envisagez de repasser temporairement à la version [v1.6.1](https://rbr-masterclass.de/roadbook-versions.html) le temps que j’en sache plus.

Aucun problème confirmé pour l’instant — il s’agit simplement d’une mesure de précaution.

---

## ⚙️ Incompatibilité de l'outil de calibration avec Simucube Tuner

Actuellement, **Simucube Tuner** utilise le port UDP de télémétrie NGP par défaut, ce qui empêche Pacenote Lab de récupérer les données de télémétrie.

Une future mise à jour permettra de personnaliser le port d'écoute, ce qui réglera ce conflit.


