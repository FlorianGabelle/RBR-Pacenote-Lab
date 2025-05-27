---
layout: article
title: "RSF Telemetry Settings"
excerpt: "Prerequisites"
show_date: false
lang: en
type: doc
order: 20
cover: /assets/images/docs/en/rsf_window/telemetry.png
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

{% include image.html
   src="/assets/images/docs/en/rsf_window/telemetry.png"
   alt="RSF Telemetry Settings"
   max_width="100%" %}

---

If you need to listen to the UDP data on an additional port—perhaps because another application like your wheelbase software or SimHub is already using the default port—you can define an extra port in the settings. This allows multiple tools to receive telemetry simultaneously without conflicts.

To do this, add a secondary UDP port in the configuration (e.g., 127.0.0.1:6777) and ensure that you **update** the UDP telemetry settings accordingly in the **General settings** of the Configuration window.

{% include image.html
   src="/assets/images/docs/en/rsf_window/telemetry_2.png"
   alt="RSF Telemetry Settings"
   max_width="100%" %}
   
{% include image.html
   src="/assets/images/docs/en/configuration_window/general_udp_alternate.png"
   alt="RSF Telemetry Settings"
   max_width="100%" %}
