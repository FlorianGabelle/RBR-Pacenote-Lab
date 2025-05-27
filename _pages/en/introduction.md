---
layout: page
title: Introduction
lang: en
show_date: false
---

**RBR Pacenote Lab** is a data-driven tool for generating fully customizable co-driver pacenotes for the *Richard Burns Rally* simulator. It offers precision, flexibility, and full compatibility with any co-driver system.

Save up to 75% of your time — if creating notes for a 15 km stage used to take over 2 hours, expect to finish in just 30–45 minutes.

If existing pacenotes don’t suit your driving style, or if building your own feels too complex, this tool can help.
It lets you generate a clean, personalized base with minimal effort — no need to start from scratch.

Let the software handle the precision and structure so you can focus on reviewing and refining.

---

## 🗒️ Pacenote contents

Generated pacenotes include:

- Corner links — e.g., *into*, *and*
- Corner calls — numeric, descriptive, or custom
- Modifiers — optional plus/minus notation (even for unsupported co-drivers)
- Corner lengths — short, long, very long
- Distance callouts — optional straight-line markers
- Stage tags — *Start*, *Split*, *Finish*, *End_of_track*

{% include image.html
   src="/assets/images/docs/en/main_window/stage_map.png"
   alt="Main window"
   max_width="100%" %}

You can fine-tune output using:

- Custom placement distances
- Adjustable steering thresholds
- Filters to ignore small or irrelevant corners

---

## 📈 Data analysis engine

Currently supports:

- Steering input
- Odometer
- GPS

Planned additions:

- Accelerometer
- Gyroscope

{% include image.html
   src="/assets/images/docs/en/main_window/steering_trace.png"
   alt="Steering View"
   max_width="100%" %}
   
---

## 🎙 Co-driver compatibility

Whether you use the original RBR co-driver, modded systems, or a custom setup, RBR Pacenote Lab adapts to your co-driver:

- Legacy co-drivers
- Community co-driver mods
- Numeric, descriptive, or custom styles

The tool automatically aligns with your co-driver’s format and structure.

### ✅ Compatible with:
- [**RBR Pacenote Plugin**](https://gvrc.de/NGP.html) by WorkerBee  
- [**RBR Roadbook**](https://rbr-masterclass.de/) by MisterArek
- [**RSF**](https://rallysimfans.hu/rbr/index.php) by the RallySimFans.hu team

**Workflow example:**  
Generate corner and distance pacenotes in **Pacenote Lab**, refine the pacenotes in **RBR Roadbook**, select the final file in **RSF Launcher**, and use it with **RBR Pacenote Plugin**.

---

## ⚙️ Steering zones

The steering zone system lets you control how turns are interpreted:

- Define custom zones with angle thresholds
- Assign pacenotes to each range
- Add modifiers (plus/minus) as needed
- Import/export presets for reuse or sharing

<div class="grid grid--p-3">
  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="{{ '/assets/images/docs/en/configuration_window/steering_zones/steering_zones_descriptive.png' | relative_url }}">
        <img
          src="{{ '/assets/images/docs/en/configuration_window/steering_zones/steering_zones_descriptive.png' | relative_url }}"
          style="width: 100%; height: auto;"
          alt="Descriptive" />
      </a>
      <figcaption style="text-align: center;">Descriptive / Rbr</figcaption>
    </figure>
  </div>

  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="{{ '/assets/images/docs/en/configuration_window/steering_zones/steering_zones_numeric.png' | relative_url }}">
        <img
          src="{{ '/assets/images/docs/en/configuration_window/steering_zones/steering_zones_numeric.png' | relative_url }}"
          style="width: 100%; height: auto;"
          alt="Numeric" />
      </a>
      <figcaption style="text-align: center;">Numeric</figcaption>
    </figure>
  </div>
</div>

---

## 🛠 Additional tools

### Visual pacenotes editor

Customize how each corner pacenote appears on the stage map and in-game — including 2D and 3D icons for visual pacenotes. Personalize visuals to match your style.

{% include image.html
   src="/assets/images/docs/en/configuration_window/visual_pacenotes_editor/default.png"
   alt="Visual Pacenotes Editor"
   max_width="80%" %}

### Calibration tool

Test and calibrate your setup using live steering angle data from your simulator.

{% include image.html
   src="/assets/images/docs/en/calibration_window/calibration_tool.png"
   alt="Calibration Tool"
   max_width="50%" %}

---

## 📚 Need help getting started?

See the [documentation]({{ "/en/documentation/" | relative_url }}) for setup guides, usage tips, and advanced configuration.
