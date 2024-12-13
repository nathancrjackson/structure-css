---
title: "The Grid system"
description: "A 12 (or 10) column system implemented with grids"
weight: 60
---

## Classes

### .gd-cont & .gd-cont12

Grid container with 12 even columns

### .gd-cont-auto & .gd-cont12-auto

Grid container with 12 auto-sized columns

### .gd-cont10

Grid container with 10 even columns

### .gd-cont10-auto

Grid container with 10 auto-sized columns

### .gd-{x}{num}

Where _{x}_ is the screen size and _{num}_ is the column width. Here is a table with all of the options:

|   | Small | Medium | Large |
|---|---|---|---|
| _1_ | gd-s1 | gd-m1 | gd-l1 |
| _2_ | gd-s2 | gd-m2 | gd-l2 |
| _3_ | gd-s3 | gd-m3 | gd-l3 |
| _4_ | gd-s4 | gd-m4 | gd-l4 |
| _5_ | gd-s5 | gd-m5 | gd-l5 |
| _6_ | gd-s6 | gd-m6 | gd-l6 |
| _7_ | gd-s7 | gd-m7 | gd-l7 |
| _8_ | gd-s8 | gd-m8 | gd-l8 |
| _9_ | gd-s9 | gd-m9 | gd-l9 |
| _10_ | gd-s10 | gd-m10 | gd-l10 |
| _11_ | gd-s11 | gd-m11 | gd-l11 |
| _12_ | gd-s12 | gd-m12 | gd-l12 |

## Example

```html
<div class="gd-cont">
	<div class="gd-12 gd-m4">
		<p>I span the full width of a small screen but a third of a medium or larger screen</p>
	</div>
	<div class="gd-12 gd-m8">
		<p>I span the full width of a small screen but two thirds of a medium or larger screen</p>
	</div>
</div>
```