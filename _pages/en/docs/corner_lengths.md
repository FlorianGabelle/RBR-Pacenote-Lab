---
layout: article
title: "Corner Lengths"
excerpt: "Configuration"
show_date: false
lang: en
type: doc
order: 5
cover: /assets/images/docs/en/corner_lengths/settings.PNG
sidebar:
  nav: docs-en
---

The application calculates corner length using telemetry data.

Corner length is categorized as:

- Short
- Normal (no call)
- Long
- Very long

{% include image.html
   src="/assets/images/docs/en/corner_lengths/settings.PNG"
   alt="Corner Length Settings"
   max_width="80%" %}

---

### ⚙️ Configuration

For each category, you can:

- **Enable** or disable it
- Set its length **threshold**
- Assign a custom **pacenote** call

---

> 📌 Note: The computed corner length depends on the **steering detection threshold** you’ve set.  
> A lower threshold causes the system to detect corners earlier and exit later, resulting in longer calculated corners.
