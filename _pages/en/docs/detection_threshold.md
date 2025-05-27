---
layout: article
title: "Detection Threshold"
excerpt: "Analysis Settings"
show_date: false
lang: en
type: doc
order: 100
cover: /assets/images/docs/en/main_window/detection_threshold.png
sidebar:
  nav: docs-en
---

The detection threshold is a key analysis parameter. It affects several aspects of how the tool interprets your telemetry data:

- Start-of-corner detection  
- End-of-corner detection  
- Corner length calculation  
- Distances between corners (and therefore corner linking)

{% include image.html
   src="/assets/images/docs/en/main_window/detection_threshold.png"
   alt="Detection Threshold Settingl"
   max_width="100%" %}

---

### 🔽 Lowering the threshold

Reducing the threshold will:

- Allow detection of corners with **smaller** amplitudes (e.g., fast, sweeping turns)
- Result in **longer** measured corner lengths, which may reduce precision

---

### 🔼 Increasing the threshold

Raising the threshold will:

- Filter out subtle steering changes by **ignoring** low-amplitude inputs
- Improve **separation** between corners, creating clearer individual detections

---

### ✅ Recommended Setting

The default value of **10 degrees** provides a **balanced compromise**, working well with standard corner lengths, link thresholds, and distances.

You can adjust this setting based on your specific needs:

- **Decrease** the value to make detection more sensitive, which helps identify minor or fast corners.

- **Increase** the value slightly if nearby corners are being grouped together and detected as a single corner.

Lowering the detection threshold doesn’t always lead to better results or higher-quality notes. In some cases, a higher threshold can be more effective. Detecting very low-intensity corners may cause issues, such as difficulty distinguishing between consecutive, closely spaced corners.

> 📌 Note: Raw steering data is pre-processed — it’s down-sampled and filtered to reduce signal noise near the threshold level and to improve performance.
