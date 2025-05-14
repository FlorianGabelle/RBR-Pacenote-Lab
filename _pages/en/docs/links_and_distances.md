---
layout: article
title: "Links and Distances"
excerpt: "Configuration"
show_date: false
lang: en
type: doc
order: 6
cover: /assets/images/docs/en/links_and_distances/settings.png
sidebar:
  nav: docs-en
---

This section allows you to configure two key features:

- **Corner links** (e.g., *"into"*, *"and"*)
- **Distance calls**

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/docs/en/links_and_distances/settings.png">
      <img src="/assets/images/docs/en/links_and_distances/settings.png" style="display: block; margin: 0 auto; max-width: 80%;" alt="Links and Distances Settings" />
    </a>
  </figure>
</div>

---

### ⚙️ Configuration – corner links

You can enable or disable corner linking and adjust the **distance threshold** between two corners. This defines how close the corners must be to trigger a linking call (such as *"into"*).

Other options include:

- Selecting the specific link word (e.g., *"into"*, *"and"*)
- Combining the link with the previous pacenote, so both are delivered more closely together

> ⚠️ Using very low thresholds may group too many corners together in tight sections, making instructions harder to follow.

---

### ⚙️ Configuration – distance calls

You can also set up a distance call to indicate longer straights:

- Enable or disable the feature
- Define the minimum straight-line distance required to trigger the call

This can help drivers anticipate long acceleration zones or prepare for braking earlier.

---

> 📌 Note: Detected distances depend on your configured steering detection threshold.  
> A lower threshold causes corners to be detected earlier and exited later, leading to longer corner durations and shorter calculated distances.
