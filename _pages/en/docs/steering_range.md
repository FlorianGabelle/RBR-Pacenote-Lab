---
layout: article
title: "Steering Range"
excerpt: "Analysis Settings"
show_date: false
lang: en
type: doc
order: 90
cover: /assets/images/docs/en/steering_range/setting.PNG
sidebar:
  nav: docs-en
---

To ensure the in-game steering angle matches your physical wheel rotation, it's important to set the steering range value correctly.

The goal is simple:  
**One degree in-game = one degree on your wheel**

This one-to-one match provides precise, repeatable steering measurements — essential for generating consistent corner pacenotes.

{% include image.html
   src="/assets/images/docs/en/steering_range/setting.PNG"
   alt="Steering Range Setting"
   max_width="100%" %}

---

### ⚙️ Configuration

- If `"Adjust steering wheel range per car"` is enabled in RSF Launcher, use the car's steering angle value.
- If you're using `"Steering wheel lock-to-lock rotation"` in the *My Cars* section along with `"Adjust steering wheel range per car"`, use the custom value you've set to override the NGP default.
- If neither setting is enabled, use your wheel base’s steering range value.

If you're unsure or want to verify your setup, use the calibration tool included in the application. It helps fine-tune the correct range using live telemetry.

For detailed instructions, see the [Calibration tool]({{ "/en/docs/calibration_tool/" | relative_url }}) page.
