---
layout: article
title: "Problèmes connus"
excerpt: "Informations importantes"
show_date: false
lang: fr
type: doc
order: 11
cover: /assets/images/warning.png
sidebar:
  nav: docs-fr
---

## ⚠️ Incompatibilité avec la dernière version de Roadbook

À l'heure actuelle, **RBR Roadbook v1.6.2** présente des problèmes connus avec l'import/export des fichiers de pacenotes.

Plus précisément, il **remplace automatiquement** les identifiants des virages (corner pacenote IDs), ce qui peut entraîner une interprétation incorrecte de vos notes générées, selon une autre échelle.

Il est fortement recommandé de rester sur ou de revenir à la version [v1.6.1](https://rbr-masterclass.de/roadbook-versions.html) si vous prévoyez de modifier des notes générées avec **Pacenote Lab**.

---

## ⚙️ Incompatibilité de l'outil de calibration avec Simucube Tuner

Actuellement, **Simucube Tuner** utilise par défaut le port UDP de télémétrie NGP, ce qui empêche Pacenote Lab de récupérer les données de télémétrie.

Une future mise à jour permettra de personnaliser le port d'écoute, ce qui réglera ce conflit.


