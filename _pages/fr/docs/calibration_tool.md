---
layout: article
title: "Calibration du Volant"
excerpt: "Outils Additionnels"
show_date: false
lang: fr
type: doc
order: 8
cover: /assets/images/docs/fr/calibration_tool/calibration_tool.PNG
sidebar:
  nav: docs-fr
---

L’**outil de calibration** est accessible depuis l’interface principale. Il permet de vérifier que la **plage de rotation du volant** configurée dans la section d’analyse correspond bien à la plage réellement utilisée en jeu.

En lisant les données du volant en temps réel via le flux de télémétrie UDP, l’outil compare la plage configurée avec la valeur réelle du jeu.

---

### ℹ️ Comment utiliser l’outil de calibration

1. Vérifiez que la télémétrie est activée dans la fenêtre du **Launcher RSF**.  
2. Lancez l’outil lorsque vous êtes en jeu, dans une voiture, sur une spéciale.  
3. Gardez la **fenêtre du jeu active** — c’est nécessaire pour que la télémétrie soit lue.  
4. Tournez votre volant de **180 degrés vers la droite**.  
5. Cliquez sur le bouton **Calculer**.

{% include image.html
   src="/assets/images/docs/fr/calibration_tool/calibration_tool.PNG"
   alt="Outil de calibration"
   max_width="50%"
}

---

### ⚠️ Remarques importantes

- Cliquer sur **Calculer** fait perdre le focus à la fenêtre du jeu, ce qui désactive temporairement le retour de force (**FFB**).

  - Pour éviter tout risque de blessure, réduisez ou désactivez le FFB avant d’utiliser l’outil.

- Après avoir cliqué sur le bouton, vous devez **revenir dans la fenêtre du jeu** pour que la lecture de la télémétrie reprenne.

---

### ✅ Résultat attendu

Une fois de retour dans le jeu :

- Le **volant virtuel** affiché dans l’outil doit correspondre aux mouvements de votre volant réel.  
- La valeur calculée doit refléter votre [plage de rotation](/fr/docs/steering_range/) correcte, à reporter dans la section **Analyse**.
