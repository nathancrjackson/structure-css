---
title: "The Flex system"
description: "A 12 column system and a shrink/auto row system implemented with flex"
weight: 50
---

## Classes

### .fx-cont

Flex container with 12 even columns along the X axis

### .fx-{x}{num}

Where _{x}_ is the screen size and _{num}_ is the column width inside of an fx-cont element. Here is a table with all of the options:

|   | Small | Medium | Large |
|---|---|---|---|
| _1_ | fx-s1 | fx-m1 | fx-l1 |
| _2_ | fx-s2 | fx-m2 | fx-l2 |
| _3_ | fx-s3 | fx-m3 | fx-l3 |
| _4_ | fx-s4 | fx-m4 | fx-l4 |
| _5_ | fx-s5 | fx-m5 | fx-l5 |
| _6_ | fx-s6 | fx-m6 | fx-l6 |
| _7_ | fx-s7 | fx-m7 | fx-l7 |
| _8_ | fx-s8 | fx-m8 | fx-l8 |
| _9_ | fx-s9 | fx-m9 | fx-l9 |
| _10_ | fx-s10 | fx-m10 | fx-l10 |
| _11_ | fx-s11 | fx-m11 | fx-l11 |
| _12_ | fx-s12 | fx-m12 | fx-l12 |

### .fx-sshrink, .fx-mshrink, .fx-lshrink

Have the column for its respective size inside of an fx-cont element shrink to be only the size it needs to be

### .fx-sauto, .fx-mauto, .fx-lauto

Have the column for its respective size inside of an fx-cont element expand to fit the size available to it

### .fxy-cont

Flex container along the Y axis

### .fxy-shrink

Have the row for its respective size inside of an fxy-cont element shrink to be only the size it needs to be

### .fxy-auto

Have the row for its respective size inside of an fxy-cont element expand to fit the size available to it

## Examples

### Fixed column sizes

```html
<div class="fx-cont">
	<div class="fx-12 fx-m4">
		<p>I span the full width of a small screen but a third of a medium or larger screen</p>
	</div>
	<div class="fx-12 fx-m8">
		<p>I span the full width of a small screen but two thirds of a medium or larger screen</p>
	</div>
</div>
```

### Shrink/expand columns

```html
<div class="fx-cont">
	<div class="fx-12 fx-mshrink">
		<p>I span the full width of a small screen but shrink on a medium or larger screen</p>
	</div>
	<div class="fx-12 fx-mauto">
		<p>I span the full width of a small screen but expand on a medium or larger screen</p>
	</div>
</div>
```

### Shrink/expand row

```html
<body class="fxy-cont">
	<header class="fxy-shrink">
		<p>I am just the height that I need to be</p>
	</header>
	<main class="fxy-auto">
		<p>I grow to fill the height if space is available</p>
	</main>
	<footer class="fxy-shrink">
		<p>I am just the height that I need to be</p>
	</footer>
</body>
```
