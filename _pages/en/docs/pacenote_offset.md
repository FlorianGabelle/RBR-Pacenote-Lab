---
layout: article
title: "Pacenote Offset"
excerpt: "Analysis Settings"
show_date: false
lang: en
type: doc
order: 12
cover: /assets/images/docs/en/pacenote_offset/setting.PNG
sidebar:
  nav: docs-en
---

The **pacenote offset** setting lets you fine-tune the positioning of corner pacenotes on the stage map.

Since pacenote positions are determined by the corner detection algorithm, their default placement may not always match your preference — especially depending on the detection threshold.

The offset is a distance value in meters:
- A **negative value** moves the pacenote earlier (before the corner)
- A **positive value** places it further into the corner

{% include image.html
   src="/assets/images/docs/en/pacenote_offset/setting.PNG"
   alt="Pacenote Offset Setting"
   max_width="80%" %}

---

### ⚙️ Configuration

- If you're using a high detection threshold, corner entry is detected late, and pacenotes may appear too far into the corner  
  → Use a **negative offset** to shift them earlier

- If you're using a low detection threshold, corner entry is detected early, and pacenotes may appear too soon  
  → Use a **positive offset** to move them deeper into the corner

---

> 🔎 Note: This setting only affects corner pacenotes.  
> Distance calls remain positioned at the end of the preceding corner and are not affected by this offset.
