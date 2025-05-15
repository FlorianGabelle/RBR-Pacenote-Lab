---
layout: article
title: "Detection Threshold"
excerpt: "Analysis Settings"
show_date: false
lang: en
type: doc
order: 10
cover: /assets/images/docs/en/detection_threshold/setting.PNG
sidebar:
  nav: docs-en
---

The detection threshold is a key analysis parameter. It affects several aspects of how the tool interprets your telemetry data:

- Start-of-corner detection  
- End-of-corner detection  
- Corner length calculation  
- Distances between corners (and therefore corner linking)

{% include image.html
   src="/assets/images/docs/en/detection_threshold/setting.PNG"
   alt="Detection Threshold Settingl"
   max_width="100%" %}

---

### 🔽 Lowering the threshold

Reducing the threshold will:

- Allow detection of corners with smaller amplitudes (e.g., fast, sweeping turns)
- Result in longer measured corner lengths, which may reduce precision

---

### 🔼 Increasing the threshold

Raising the threshold will:

- Filter out subtle steering changes by ignoring low-amplitude inputs
- Improve separation between corners, creating clearer individual detections

---

### ✅ Recommended setting

The default value of **10 degrees** offers a balanced compromise with the standard settings for corner lengths, links, and distances.

Depending on your use case:

- Lower the value to increase sensitivity and detect more corners
- Raise the value slightly to reduce false positives or signal noise

As you become more familiar with the tool and its behavior, you can experiment with lowering the threshold to increase sensitivity.  
However, doing so may require fine-tuning your distance, corner filtering and pacenote offset settings to maintain output quality.

> 📌 Note: Raw steering data is pre-processed — it’s down-sampled and filtered to reduce signal noise near the threshold level and to improve performance.
