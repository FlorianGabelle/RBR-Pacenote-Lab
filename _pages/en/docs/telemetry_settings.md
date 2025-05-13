---
layout: article
title: "RSF Telemetry Settings"
excerpt: "Prerequisites"
show_date: false
lang: en
type: doc
order: 2
cover: assets/images/ui/en/telemetry.PNG
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

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/ui/en/telemetry.png">
      <img src="/assets/images/ui/en/telemetry.png" style="display: block; margin: 0 auto; max-width: 100%;" alt="Telemetry settings screenshot" />
    </a>
  </figure>
</div>
