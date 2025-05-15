---
layout: page
title: Introduction
lang: fr
show_date: false
---

**RBR Pacenote Lab** est un outil basé sur les données, conçu pour générer des pacenotes copilote entièrement personnalisables pour le simulateur *Richard Burns Rally*. Il offre précision, flexibilité et compatibilité totale avec tous les systèmes de copilote.

Gagnez jusqu’à 75 % de temps — si créer des notes pour une spéciale de 15 km vous prenait plus de 2 heures, attendez-vous à terminer en 30–45 minutes.

Si les notes existantes ne correspondent pas à votre style de conduite, ou si créer les vôtres vous semble trop complexe, cet outil peut vous aider.
Il vous permet de générer une base claire et personnalisée, sans repartir de zéro.

Laissez le logiciel gérer la précision et la structure — vous pouvez ensuite vous concentrer sur la relecture et les ajustements.

---

## 🗒️ Contenu des pacenotes

Les pacenotes générés incluent :

- Enchaînements — par ex. *dans*, *et*
- Appels de virage — numériques, descriptifs ou personnalisés
- Modificateurs — plus/moins (fonctionne même avec des copilotes non compatibles)
- Longueurs de virage — court, long, très long
- Annonces de distance — repères optionnels sur les lignes droites
- Marqueurs de spéciale — *Start*, *Split*, *Finish*, *End_of_track*

{% include image.html
   src="/assets/images/docs/fr/introduction/main_window.PNG"
   alt="Fenêtre principale"
   max_width="100%" %}

Vous pouvez affiner le résultat avec :

- Des distances personnalisées pour le placement
- Des seuils de détection d'angle du volant ajustables
- Des filtres pour ignorer les virages mineurs ou non pertinents

---

## 📈 Moteur d’analyse des données

Actuellement compatible avec :

- Angle du volant
- Compteur kilométrique
- GPS

Fonctionnalités prévues :

- Accéléromètre
- Gyroscope

{% include image.html
   src="/assets/images/docs/fr/introduction/steering.PNG"
   alt="Courbe du volant"
   max_width="100%" %}

---

## 🎙 Compatibilité copilote

Que vous utilisiez le copilote d’origine, un mod communautaire ou votre propre configuration, RBR Pacenote Lab s’adapte :

- Copilotes « legacy »
- Mods de copilotes communautaires
- Styles numériques, descriptifs ou personnalisés

L’outil s’aligne automatiquement avec le format et la structure de votre copilote.

### ✅ Compatible avec :
- [**RBR Pacenote Plugin**](https://gvrc.de/NGP.html) par WorkerBee  
- [**RBR Roadbook**](https://rbr-masterclass.de/) par MisterArek  
- [**RSF**](https://rallysimfans.hu/rbr/index.php) par l’équipe de RallySimFans.hu

**Exemple de processus :**  
Générez les notes de virage et de distance dans **Pacenote Lab**, affinez les notes dans **RBR Roadbook**, sélectionnez le fichier final dans le **RSF Launcher**, et utilisez-le avec le **RBR Pacenote Plugin**.

---

## ⚙️ Zones volant

Le système de zones volant vous permet de définir comment les virages sont interprétés :

- Définissez des zones personnalisées avec des seuils d’angle
- Assignez un appel à chaque plage
- Ajoutez des modificateurs (plus/moins) si nécessaire
- Importez/exportez des préréglages à partager ou réutiliser

<div class="grid grid--p-3">
  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="{{ '/assets/images/docs/fr/introduction/steering_zones_descriptive.PNG' | relative_url }}">
        <img
          src="{{ '/assets/images/docs/fr/introduction/steering_zones_descriptive.PNG' | relative_url }}"
          style="width: 100%; height: auto;"
          alt="Zones volant - Descriptif" />
      </a>
      <figcaption style="text-align: center;">Descriptif / Rbr</figcaption>
    </figure>
  </div>

  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="{{ '/assets/images/docs/fr/introduction/steering_zones_numeric.PNG' | relative_url }}">
        <img
          src="{{ '/assets/images/docs/fr/introduction/steering_zones_numeric.PNG' | relative_url }}"
          style="width: 100%; height: auto;"
          alt="Zones volant - Numérique" />
      </a>
      <figcaption style="text-align: center;">Numérique</figcaption>
    </figure>
  </div>
</div>

---

## 🛠 Outils additionnels

### Éditeur Graphique de Notes

Personnalisez comment chaque appel est représenté sur la carte et en jeu — y compris les icônes 2D et 3D. Ajustez les visuels selon votre système.

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/docs/fr/introduction/pacenote_graphics_editor.PNG">
      <img src="/assets/images/docs/fr/introduction/pacenote_graphics_editor.PNG" style="display: block; margin: 0 auto; max-width: 80%;" alt="Editeur de notes graphiques" />
    </a>
  </figure>
</div>

{% include image.html
   src="/assets/images/docs/fr/introduction/pacenote_graphics_editor.PNG"
   alt="Editeur de notes graphiques"
   max_width="80%" %}

### Outil de calibration

Testez et calibrez votre configuration à l’aide des données de rotation du volant en temps réel issues du simulateur.

{% include image.html
   src="/assets/images/docs/fr/calibration_tool/calibration_tool.PNG"
   alt="Outil de calibration"
   max_width="50%" %}

---

## 📚 Besoin d’aide pour démarrer ?

Consultez la [documentation]({{ "/fr/documentation/" | relative_url }}) pour les guides de configuration, conseils d’utilisation et options avancées.
