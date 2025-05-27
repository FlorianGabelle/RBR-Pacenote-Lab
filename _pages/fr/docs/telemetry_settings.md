---
layout: article
title: "Configuration de la télémétrie RSF"
excerpt: "Prérequis"
show_date: false
lang: fr
type: doc
order: 20
cover: /assets/images/docs/fr/rsf_window/telemetry.png
sidebar:
  nav: docs-fr
---

Pour activer l’analyse et générer les pacenotes, assurez-vous que les paramètres RSF suivants sont définis :

- Enregistrer les données télémétriques dans un fichier : `Activé`  
- Intervalle de mise à jour : `5`  
- Position de la voiture en spéciale : `Activé`  
- Keep only MoTeC files : `Désactivé`

> ⚠️ Ces paramètres sont susceptibles d’évoluer dans les prochaines versions, à mesure que de nouveaux capteurs seront pris en charge par le moteur d’analyse.

---

Pour utiliser l’**outil de calibration**, appliquez ces réglages :

- Télémétrie UDP : `Activé`  
- 127.0.0.1:6776

{% include image.html
   src="/assets/images/docs/fr/rsf_window/telemetry.png"
   alt="Télémétrie RSF"
   max_width="100%" %}

---

Si vous avez besoin d'écouter les données UDP sur un port supplémentaire — par exemple si une autre application comme le logiciel de votre base de volant ou SimHub utilise déjà le port par défaut — vous pouvez définir un port supplémentaire dans les paramètres. Cela permet à plusieurs outils de recevoir la télémétrie en même temps, sans conflit.

Pour ce faire, ajoutez un port UDP secondaire dans la configuration (par exemple, 127.0.0.1:6777) et assurez-vous de **mettre à jour** les paramètres de télémétrie UDP en conséquence dans l'onglet **Général** de la fenêtre de configuration.

{% include image.html
   src="/assets/images/docs/fr/rsf_window/telemetry_2.png"
   alt="RSF Telemetry Settings"
   max_width="100%" %}
   
{% include image.html
   src="/assets/images/docs/fr/configuration_window/general_udp_alternate.png"
   alt="RSF Telemetry Settings"
   max_width="100%" %}

