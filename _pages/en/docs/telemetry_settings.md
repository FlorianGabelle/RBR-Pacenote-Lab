---
layout: article
title: "RSF Telemetry Settings"
excerpt: "Prerequisites"
show_date: false
lang: en
type: doc
order: 2
cover: /assets/images/docs/en/telemetry/settings.png
sidebar:
  nav: docs-en
---

To enable analysis and generate pacenotes, make sure the following RSF settings are configured:

- Record telemetry data in a file: `Enabled`
- Update interval: `5`
- Car map position: `Enabled`
- Keep only MoTeC files: `Disabled`

> ⚠️ These settings may change in future versions as more sensors are integrated into the processing engine.

---

For the calibration tool, use these settings:

- UDP telemetry: `Enabled`
- 127.0.0.1:6776

---

{% include image.html
   src="/assets/images/docs/en/telemetry/settings.png"
   alt="RSF Telemetry Settings"
   max_width="100%" %}