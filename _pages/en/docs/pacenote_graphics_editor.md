---
layout: article
title: "Pacenote Graphics Editor"
excerpt: "Additional Tools"
show_date: false
lang: en
type: doc
order: 140
cover: /assets/images/docs/en/pacenote_graphics_editor/default.PNG
sidebar:
  nav: docs-en
---

The pacenote graphics editor is located in the configuration window. It allows you to customize which icons appear on the stage map and in-game for each pacenote call by modifying your co-driver’s package files.

You can select a pacenote package using the **Current package** dropdown. Each package defines a set of pacenote calls used by your co-driver.

{% include image.html
   src="/assets/images/docs/en/pacenote_graphics_editor/default.PNG"
   alt="Pacenote Graphics Editor"
   max_width="80%" %}

---

### ℹ️ How to use the graphics editor

For each pacenote, the default pacenote graphic is shown based on its unique **pacenote ID**.
You may already see modified pacenote graphics if the co-driver mod author included custom standard calls.

To override or add a pacenote graphic:
- Select a new graphic from the dropdown menu on the right side of the row.

> 💾 Don’t forget to click **Save** after making changes.  
> Each package must be saved individually.

{% include image.html
   src="/assets/images/docs/en/pacenote_graphics_editor/combobox.PNG"
   alt="Graphics Selection Dropdown"
   max_width="80%" %}

---

⚠️ **Important**

The updated graphics system relies on two components:

1. Modified co-driver package files
2. Flags in the pacenote file for the stage

To ensure your updated icons appear in-game, you must:
- Generate the pacenote file using *RBR Pacenote Lab*, or  
- Import and re-export existing pacenote files via *RBR Roadbook* after patching your package files with this tool
