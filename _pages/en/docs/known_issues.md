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

## ⚠️ Incompatibility with Latest Version of Roadbook

As of now, **RBR Roadbook v1.6.2** has known issues with pacenote file import/export.

Specifically, it **overwrites** corner pacenote IDs, which may cause your generated notes to be interpreted using a different scale.

It is strongly recommended to stay on or revert to [v1.6.1](https://rbr-masterclass.de/roadbook-versions.html) if you plan to edit notes generated with **Pacenote Lab**.

---

## ⚙️ Calibration Tool Incompatibility with Simucube Tuner

Currently, **Simucube Tuner** uses the default NGP telemetry UDP port, preventing Pacenote Lab from retrieving telemetry data.

A future update will allow you to customize the listening port, resolving this conflict.
