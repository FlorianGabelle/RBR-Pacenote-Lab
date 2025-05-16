---
layout: article
title: "Known Issues"
excerpt: "Important Information"
show_date: false
lang: en
type: doc
order: 11
cover: /assets/images/warning.png
sidebar:
  nav: docs-en
---

## ⚠️ Note on Compatibility with Roadbook v1.6.2

**RBR Roadbook v1.6.2** should work fine for most use cases, including pacenote file import/export with **Pacenote Lab**.

However, in rare cases, it *might* overwrite corner pacenote IDs, which could lead to notes being interpreted using a different scale.

### What to Do (Just in Case)
If you notice anything unusual with your notes after importing, consider temporarily switching back to [v1.6.1](https://rbr-masterclass.de/roadbook-versions.html) while I investigate further.

No confirmed issues yet—this is just a precaution.

---

## ⚙️ Calibration Tool Incompatibility with Simucube Tuner

Currently, **Simucube Tuner** uses the default NGP telemetry UDP port, preventing Pacenote Lab from retrieving telemetry data.

A future update will allow you to customize the listening port, resolving this conflict.
