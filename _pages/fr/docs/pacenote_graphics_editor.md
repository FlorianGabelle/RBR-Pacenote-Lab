---
layout: article
title: "Éditeur de notes graphiques"
excerpt: "Outils Additionnels"
show_date: false
lang: fr
type: doc
order: 140
cover: /assets/images/docs/fr/pacenote_graphics_editor/default.PNG
sidebar:
  nav: docs-fr
---

L’**éditeur de notes graphiques** se trouve dans la fenêtre de configuration. Il vous permet de personnaliser les icônes affichées sur la carte et en jeu pour chaque appel, en modifiant les fichiers package de votre copilote.

Vous pouvez sélectionner un **package de pacenotes** via le menu déroulant **Package actuel**. Chaque package contient un ensemble d’appels utilisés par votre copilote.


{% include image.html
   src="/assets/images/docs/fr/pacenote_graphics_editor/default.PNG"
   alt="Éditeur de notes graphiques"
   max_width="80%" %}

---

### ℹ️ Comment utiliser l’éditeur graphique

Pour chaque appel, l'icône de pacenote par défaut est affichée selon son **ID unique**.  
Vous verrez peut-être déjà des icônes personnalisées si le créateur du mod copilote a renseigné des appels "standards" spécifiques.

Pour modifier ou ajouter une icône :
- Sélectionnez une nouvelle icône dans le menu déroulant à droite de la ligne correspondante.

> 💾 N’oubliez pas de cliquer sur **Enregistrer** après chaque modification.  
> Chaque package doit être enregistré individuellement.

{% include image.html
   src="/assets/images/docs/fr/pacenote_graphics_editor/combobox.PNG"
   alt="Menu déroulant des icônes"
   max_width="80%" %}

---

⚠️ **Important**

Le système de graphiques personnalisés repose sur deux éléments :

1. Les fichiers de package du copilote modifiés  
2. Les indicateurs (flags) dans le fichier pacenotes associé à la spéciale

Pour que les icônes s’affichent correctement en jeu, vous devez :
- Générer le fichier pacenotes via *RBR Pacenote Lab*, ou  
- Importer puis réexporter vos fichiers existants via *RBR Roadbook*, après avoir mis à jour les fichiers package avec cet outil
