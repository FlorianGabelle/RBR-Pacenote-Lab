---
layout: article
title: "Calibration Tool"
excerpt: "Additional Tools"
show_date: false
lang: en
type: doc
order: 130
cover: /assets/images/docs/en/calibration_window/calibration_tool.png
sidebar:
  nav: docs-en
---

The calibration tool is accessible from the main interface. It helps verify that the **steering range** configured in the analysis section matches the actual range used in-game.

By reading live steering data from the UDP telemetry stream, the tool compares your configured steering range against real-time input from the game.

---

### ℹ️ How to use the calibration tool

1. Make sure telemetry is enabled in the **RSF Launcher** window.
2. Launch the tool while you're in-game, seated in a car, and on a stage.
3. Keep the **game window in focus** — this is required for the tool to read telemetry.
4. Rotate your steering wheel 180 degrees to the right.
5. Click the **Compute** button.

{% include image.html
   src="/assets/images/docs/en/calibration_window/calibration_tool.png"
   alt="Calibration Tool"
   max_width="50%" %}

---

### ⚠️ Important notes

- Clicking **Compute** causes the game window to lose focus, which in turn temporarily disables force feedback (FFB).

  - To avoid injury, reduce or disable FFB before using the tool.

- After clicking, you must **return focus to the game window** for telemetry reading to resume.

---

### ✅ Expected result

Once you're back in the game window:

- The **virtual steering wheel** in the calibration tool should match your physical wheel.
- The computed value should reflect your correct **steering range**, and this value should be used in the **analysis** section.
