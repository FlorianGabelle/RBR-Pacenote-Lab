---
layout: article
title: "Steering Range"
excerpt: "Analysis Settings"
show_date: false
lang: en
type: doc
order: 90
cover: /assets/images/docs/en/main_window/steering_range.png
sidebar:
  nav: docs-en
---

To ensure the in-game steering angle matches your physical wheel rotation, it's important to set the steering range value correctly.

The goal is simple:  
**One degree in-game = one degree on your wheel**

This one-to-one match provides precise, repeatable steering measurements — essential for generating consistent corner pacenotes.

{% include image.html
   src="/assets/images/docs/en/main_window/steering_range.png"
   alt="Steering Range Setting"
   max_width="100%" %}

---

### ⚙️ Configuration

- If `"Adjust steering wheel range per car"` is enabled in RSF Launcher, use the car's steering angle value.
- If you're using `"Steering wheel lock-to-lock rotation"` in the *My Cars* section along with `"Adjust steering wheel range per car"`, use the custom value you've set to override the NGP default.
- If neither setting is enabled, use your wheel base’s steering range value.

If you're unsure or want to verify your setup, use the calibration tool included in the application. It helps fine-tune the correct range using live telemetry.

For detailed instructions, see the [Calibration tool]({{ "/en/docs/calibration_tool/" | relative_url }}) page.

---

### ⚠️ Important Note

If you override the NGP default with a lower steering range value, or set your wheel base to a value smaller than the car’s defined range, it will affect the scale of the measurements. Since the wheel needs to be turned less to reach the same in-game angle, the resulting telemetry values will be proportionally smaller. This reduces the granularity of the data, meaning fewer distinct values are captured across the steering range.
While this doesn't impact accuracy or consistency, it does reduce measurement detail. For this reason, it's recommended to stick to the NGP default values during recces to preserve measurement resolution.