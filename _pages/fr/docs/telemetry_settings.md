---
layout: article
title: "Configuration de la télémétrie RSF"
excerpt: "Prérequis"
show_date: false
lang: fr
type: doc
order: 2
cover: /assets/images/docs/fr/telemetry_settings/telemetry.png
sidebar:
  nav: docs-fr
---

Pour activer l’analyse et générer les pacenotes, assurez-vous que les paramètres RSF suivants sont définis :

- **Enregistrer les données télémétriques dans un fichier** : `Activé`  
- **Intervalle de mise à jour** : `5`  
- **Position de la voiture en spéciale** : `Activé`  
- **Keep only MoTeC files** : `Désactivé`

> ⚠️ Ces paramètres sont susceptibles d’évoluer dans les prochaines versions, à mesure que de nouveaux capteurs seront pris en charge par le moteur d’analyse.

---

Pour utiliser l’**outil de calibration**, appliquez ces réglages :

- **Télémétrie UDP** : `Activé`  
- **127.0.0.1:6776**

---

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/docs/fr/telemetry_settings/telemetry.png">
      <img src="/assets/images/docs/fr/telemetry_settings/telemetry.png" style="display: block; margin: 0 auto; max-width: 100%;" alt="Télémétrie RSF" />
    </a>
  </figure>
</div>
