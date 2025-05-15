---
layout: article
title: "Zones volant"
excerpt: "Configuration"
show_date: false
lang: fr
type: doc
order: 4
cover: /assets/images/docs/fr/steering_zones/steering_zones_numeric.PNG
sidebar:
  nav: docs-fr
---

Les **zones volant** permettent de catégoriser les virages selon l’angle appliqué au volant. Lorsque vous passez un virage, le système enregistre l’angle de rotation du volant maximal et déclenche l’appel correspondant à la plage définie.

---

### ⚙️ Configuration

Cliquez sur le bouton **Ajouter une zone volant** pour définir votre première plage d’angle. Cela crée une zone initiale entre la position neutre (0°) et le seuil que vous avez choisi (par exemple: 14°). Vous pouvez attribuer des appels pour la gauche et la droite à chaque zone.

{% include image.html
   src="/assets/images/docs/fr/steering_zones/first_zone.PNG"
   alt="Première zone"
   max_width="80%" %}

Vous pouvez ensuite ajouter d’autres zones. Par exemple, si vous définissez une nouvelle zone à 43°, elle s’étendra depuis la fin de la précédente (ex. 14°) jusqu’à 43°.

{% include image.html
   src="/assets/images/docs/fr/steering_zones/second_zone.PNG"
   alt="Deuxième zone"
   max_width="80%" %}

Vous pouvez également définir des modificateurs (ex. *plus* ou *moins*) pour ajouter de la nuance — utile si votre copilote ne les gère pas nativement. Par exemple, la deuxième zone peut être subdivisée en trois plages plus fines grâce aux modificateurs.

{% include image.html
   src="/assets/images/docs/fr/steering_zones/modifier.PNG"
   alt="Exemple de modificateur"
   max_width="80%" %}

> ✅ Recommandation : définissez vos zones principales (par exemple, de **6 à 1**) jusqu’à environ **160–180 degrés**.

Tout angle supérieur à la dernière zone définie activera l’appel de cette dernière.  
Pour couvrir ces cas, ajoutez une zone finale à la fin — appelée par exemple **épingle**.

Vous pouvez ajuster ces appels plus tard dans **RBR Roadbook**, selon qu’il s’agit d’une équerre, d’une épingle ou d’une épingle serrée.

---

### 🔁 Import / Export

Utilisez les boutons d’import/export de l’interface pour sauvegarder ou charger vos configurations.

> ⚠️ Remarques :  
> - Vous pouvez importer n’importe quelle configuration créée avec cet outil.  
> - Si elle a été faite pour un autre système de copilote, les zones seront importées correctement, mais les appels devront peut-être être réassignés.

---

### 📂 Exemples de configurations

Voici deux fichiers de zones prêts à l’emploi, basés sur mon overlay Simhub **6–1** (lien à venir). Vous pouvez les importer directement dans l'application :

- Le premier est compatible avec les configurations descriptives et RBR (legacy).  
- Le second utilise un système d’appels numériques.

<a href="{{ '/assets/files/steering_zones_Descriptive_Rbr.csv' | relative_url }}" class="button button--primary--pill" download>
  <i class="fas fa-download"></i> steering_zones_Descriptive_Rbr.csv
</a>

<a href="{{ '/assets/files/steering_zones_Numeric.csv' | relative_url }}" class="button button--primary--pill" download>
  <i class="fas fa-download"></i> steering_zones_Numeric.csv
</a>

<div class="grid grid--p-3">
  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="{{ '/assets/images/docs/fr/steering_zones/steering_zones_descriptive.PNG' | relative_url }}">
        <img
          src="{{ '/assets/images/docs/fr/steering_zones/steering_zones_descriptive.PNG' | relative_url }}"
          style="width: 100%; height: auto;"
          alt="Mode descriptif" />
      </a>
      <figcaption style="text-align: center;">Descriptif / RBR</figcaption>
    </figure>
  </div>

  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="{{ '/assets/images/docs/fr/steering_zones/steering_zones_numeric.PNG' | relative_url }}">
        <img
          src="{{ '/assets/images/docs/fr/steering_zones/steering_zones_numeric.PNG' | relative_url }}"
          style="width: 100%; height: auto;"
          alt="Mode numérique" />
      </a>
      <figcaption style="text-align: center;">Numérique</figcaption>
    </figure>
  </div>
</div>
