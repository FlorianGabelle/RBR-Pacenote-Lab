---
layout: article
title: "Steering Trace"
excerpt: "Visualization"
show_date: false
lang: en
type: doc
order: 80
cover: /assets/images/docs/en/main_window/steering_trace.png
sidebar:
  nav: docs-en
---

The **steering trace** is a diagnostic tool that visualizes your steering input during a recce and helps you understand how corners are detected during analysis. While it may look complex at first—especially if you're new to telemetry—it offers valuable insight into the raw data behind your pacenotes.  
It can help you assess the quality of your steering input, understand why a corner was detected in a certain way, and identify whether your analysis settings need adjustment.

{% include image.html
   src="/assets/images/docs/en/main_window/steering_trace.png"
   alt="Steering View"
   max_width="100%" %}

---

### 🟥🟦 Visual elements

- Red horizontal lines represent the detection threshold, as set in your analysis settings  
- Blue segments show the detected corners

> ℹ️ You may notice that blue segments don’t start or end exactly when the trace crosses the threshold lines.  
> This is due to down-sampling and the use of distance-based (rather than time-based) sampling — a design choice for consistency and performance across different setups.

> ⚙️ Tip: Use the steering trace together with the stage map to fine-tune detection and validate corner accuracy.

---

### 🖱️ Mouse controls

The same interactions apply here as on the stage map:

- **Left-click + drag** — pan the view  
- **Scroll wheel** — zoom in or out  
- **Right-click** — reset to default zoom
