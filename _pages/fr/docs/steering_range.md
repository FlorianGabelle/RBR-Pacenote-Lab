---
layout: article
title: "Plage de rotation du volant"
excerpt: "Paramètres d’analyse"
show_date: false
lang: fr
type: doc
order: 90
cover: /assets/images/docs/fr/main_window/steering_range.png
sidebar:
  nav: docs-fr
---

Pour garantir que l’angle de rotation du volant en jeu corresponde à la rotation réelle de votre volant, il est important de bien configurer la plage de rotation.

L’objectif est simple :  
**Un degré en jeu = un degré sur votre volant**

Cette correspondance 1:1 permet des mesures précises et reproductibles — essentielles pour générer des notes cohérentes.

{% include image.html
   src="/assets/images/docs/fr/main_window/steering_range.png"
   alt="Plage de rotation"
   max_width="100%" %}

---

### ⚙️ Configuration

- Si l’option `Activer la rotation du volant automatiquement par voiture` est activée dans RSF Launcher, utilisez la valeur de l’angle de direction de la voiture.    
- Si vous utilisez `Rotation visuelle du volant` dans la section *Mes Voitures* avec `Activer la rotation du volant automatiquement par voiture`, utilisez la valeur que vous avez définie pour remplacer la valeur par défaut de NGP.    
- Si aucune de ces options n’est activée, utilisez la valeur d’angle de rotation de votre base de volant.


Si vous avez un doute ou souhaitez vérifier votre configuration, utilisez l’outil de calibration inclus dans l’application. Il vous aide à détecter la plage correcte à l’aide de la télémétrie en temps réel.


Pour plus de détails, consultez la page [Outil de calibration]({{ "/fr/docs/calibration_tool/" | relative_url }}).

---

### ⚠️ Important

Si vous remplacez la valeur par défaut de NGP par une valeur de plage de rotation plus faible, ou si vous définissez une valeur inférieure à celle prévue pour le véhicule dans les réglages de votre base de volant, cela affectera l’échelle des mesures. Étant donné que le volant devra être tourné moins pour atteindre le même angle en jeu, les valeurs de télémétrie seront proportionnellement plus faibles. Cela réduit la granularité des données, c’est-à-dire qu’il y aura moins de valeurs distinctes enregistrées sur toute la plage de rotation.
Cela n’affecte pas la précision ni la cohérence des mesures, mais diminue le niveau de détail. Il est donc recommandé de conserver les valeurs par défaut de NGP lors des reconnaissances pour préserver la résolution des mesures.
