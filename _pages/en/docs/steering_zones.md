---
layout: article
title: "Steering Zones"
excerpt: "Configuration"
show_date: false
lang: en
type: doc
order: 4
cover: /assets/images/docs/en/steering_zones/steering_zones_numeric.PNG
sidebar:
  nav: docs-en
---

Steering zones are used to categorize corners based on the amount of steering input. As you drive through a corner, the system records the maximum steering angle and announces the pacenote assigned to the matching range.

---

### ⚙️ Configuration

Click the **Add a steering zone** button to define your first angle range. This sets up the initial zone from the neutral (0°) position up to your chosen threshold (for example: 14°). You can assign left and right pacenote calls for each zone.

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/docs/en/steering_zones/first_zone.PNG">
      <img src="/assets/images/docs/en/steering_zones/first_zone.PNG" style="display: block; margin: 0 auto; max-width: 80%;" alt="First zone" />
    </a>
  </figure>
</div>

You can then add more zones. For example, if you define a new angle at 43°, that becomes the end of the next zone, starting from the previous limit (e.g., 14°).

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/docs/en/steering_zones/second_zone.PNG">
      <img src="/assets/images/docs/en/steering_zones/second_zone.PNG" style="display: block; margin: 0 auto; max-width: 80%;" alt="Second zone" />
    </a>
  </figure>
</div>

You can also define modifier calls (e.g., *plus* or *minus*) to add nuance — useful if your co-driver doesn't natively support them. For instance, the second zone could be divided into three finer ones using modifiers.

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/docs/en/steering_zones/modifier.PNG">
      <img src="/assets/images/docs/en/steering_zones/modifier.PNG" style="display: block; margin: 0 auto; max-width: 80%;" alt="Modifier Example" />
    </a>
  </figure>
</div>

> ✅ Recommendation: Define your main zones (e.g., 6 to 1) up to around 160–180 degrees.

Any steering input beyond the final zone will trigger the last assigned call. To handle this, add a catch-all zone at the end — usually labeled as a **hairpin**.

You can review and fine-tune these calls later in **RBR Roadbook**, adjusting for square corners, hairpins, or acute hairpins.

---

### 🔁 Import & export

Use the import and export buttons in the interface to manage your configurations.

> ⚠️ Note:  
> - You can import any configuration created with this tool.  
> - If it was made for a different co-driver system, the zones will import correctly, but pacenote calls may need reassignment.

---

### 📂 Sample configurations

Below are two ready-to-use zone files based on my 6–1 SimHub steering overlay (link coming soon). These can be imported directly into the app:

- The first is compatible with descriptive and RBR (legacy) co-driver setups.
- The second uses a numeric call system.

<a href="/assets/files/steering_zones_Descriptive_Rbr.csv" class="button button--primary--pill" download>
  <i class="fas fa-download"></i> steering_zones_Descriptive_Rbr.csv
</a>

<a href="/assets/files/steering_zones_Numeric.csv" class="button button--primary--pill" download>
  <i class="fas fa-download"></i> steering_zones_Numeric.csv
</a>

<div class="grid grid--p-3">
  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="/assets/images/docs/en/steering_zones/steering_zones_descriptive.PNG">
        <img src="/assets/images/docs/en/steering_zones/steering_zones_descriptive.PNG" style="width: 100%; height: auto;" alt="Descriptive" />
      </a>
      <figcaption style="text-align: center;">Descriptive / Rbr</figcaption>
    </figure>
  </div>
  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="/assets/images/docs/en/steering_zones_steering_zones/numeric.PNG">
        <img src="/assets/images/docs/en/steering_zones/steering_zones_numeric.PNG" style="width: 100%; height: auto;" alt="Numeric" />
      </a>
      <figcaption style="text-align: center;">Numeric</figcaption>
    </figure>
  </div>
</div>
