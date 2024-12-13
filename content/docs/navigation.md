---
title: "Navigation"
description: "Simple navigation menus"
weight: 70
---

## Classes

### .hnav

Apply this to a `<ul>` element to turn it into a horizontal navigation bar. Currently does not support nested menus.

### .vnav

Apply this to a `<ul>` element to turn it into a vertical navigation bar. Currently does not support nested menus.

### .rnav

Apply this to a `<ul>` element to turn it into a responsive navigation bar. On small screens the layout will be vertical and on larger screens it will be horizontal. Currently does not support nested menus.

## Example

```html
<nav>
	<ul class="rnav">
		<li class="active">Home</li>
		<li><a href="/about">About Us</a></li>
		<li class="disabled">Contact</li>
	</ul>
</nav>
```