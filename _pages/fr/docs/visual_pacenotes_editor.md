---
layout: article
title: "Éditeur de notes visuelles"
excerpt: "Outils Additionnels"
show_date: false
lang: fr
type: doc
order: 140
cover: /assets/images/docs/fr/configuration_window/visual_pacenotes_editor/default.png
sidebar:
  nav: docs-fr
---

L’**éditeur de notes visuelles** se trouve dans la fenêtre de configuration. Il vous permet de personnaliser les icônes affichées sur la carte et en jeu pour chaque appel, en modifiant les fichiers package de votre copilote.

Vous pouvez sélectionner un **package de pacenotes** via le menu déroulant **Package sélectionné**. Chaque package contient un ensemble d’appels utilisés par votre copilote.


{% include image.html
   src="/assets/images/docs/fr/configuration_window/visual_pacenotes_editor/default.png"
   alt="Éditeur de notes visuelles"
   max_width="80%" %}

---

### ℹ️ Comment utiliser l’éditeur de notes visuelles

Pour chaque appel, l'icône de pacenote par défaut est affichée selon son **ID unique**.  
Vous verrez peut-être déjà des icônes personnalisées si le créateur du mod copilote a renseigné des appels "standards" spécifiques.

Pour modifier ou ajouter une icône :
- Sélectionnez une nouvelle icône dans le menu déroulant à droite de la ligne correspondante.

> 💾 N’oubliez pas de cliquer sur **Enregistrer** après chaque modification.  
> Chaque package doit être enregistré individuellement.

{% include image.html
   src="/assets/images/docs/fr/configuration_window/visual_pacenotes_editor/combobox.png"
   alt="Menu déroulant des icônes"
   max_width="80%" %}

---

### ⚠️ Important

Le système d'icônes mis à jour repose sur deux éléments :

- Des fichiers de package copilote modifiés  
- Des indicateurs (flags) dans le fichier de pacenotes de la spéciale  

Pour que vos icônes mises à jour apparaissent en jeu, vous devez :

- Générer le fichier de pacenotes avec **RBR Pacenote Lab**, ou  
- Importer puis réexporter les fichiers de pacenotes existants via **RBR Roadbook** *après* avoir patché vos fichiers packages avec cet outil  
- **Alternativement**, vous pouvez utiliser l’**outil de patch intégré** pour régénérer les flags dans vos fichiers de pacenotes. Vous pouvez patcher un fichier unique ou tous les fichiers contenus dans le dossier `Plugins\NGPCarMenu\MyPacenotes`.

> 💡 Il est recommandé de créer une sauvegarde de vos fichiers avant d’effectuer le patch, au cas où vous auriez besoin de revenir en arrière.

