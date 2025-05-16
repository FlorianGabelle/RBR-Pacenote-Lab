---
layout: article
title: "Minimum Corner Length"
excerpt: "Analysis Settings"
show_date: false
lang: en
type: doc
order: 110
cover: /assets/images/docs/en/minimum_corner_length/setting.PNG
sidebar:
  nav: docs-en
---

The **minimum corner length** setting filters out short, potentially unwanted corners during analysis.

These brief detections can be caused by:

- Signal noise
- Sudden or unintended steering inputs

Adjusting this value helps remove false positives and improve the clarity of your pacenotes.

{% include image.html
   src="/assets/images/docs/en/minimum_corner_length/setting.PNG"
   alt="Minimum Corner Length Setting"
   max_width="100%" %}

---

### ⚙️ Configuration

- **Increase** the value to ignore very short or insignificant turns
- **Decrease** it if valid tight corners (e.g., hairpins) are being excluded

> 💡 Tip: When tuning this setting, zoom in on hairpins and square corners in the map view. This helps ensure sharp, legitimate turns aren’t mistakenly filtered out.
