# Documentation

## Lingo

Structure.CSS uses the following Lingo

| Shorthand | Expanded |
|---|---|
| blck | Block |
| cont | Container |
| gd | Grid |
| s | Small |
| m | Medium |
| l | Large |


## Body blocks

### .body-blck

Block that spans the width of its container that is intended to be used directly in the `<body>` element.

### .body-cont

A container to be used within `.body-blck` that spans `$medium-max` wide.

### .body-cont-full

A container to be used within `.body-blck` that spans the full width of `.body-blck`.

### Body blocks example

```
<div class="body-blck">
	<div class="body-cont">
		<h1>Welcome to my site</h1>
	</div>
</div>
```


## Grids

### .gd-cont & .gd-cont12

Grid container with 12 even columns

### .gd-cont-auto & .gd-cont12-auto

Grid container with 12 auto-sized columns

### .gd-cont10

Grid container with 10 even columns

### .gd-cont10-auto

Grid container with 10 auto-sized columns

### .gd-_xy_

Where _x_ is the screen size and _y_ is the column width. Here is a table with all of the options:

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

### Grids example

```
<div class="gd-cont">
	<div class="gd-12 gd-m4">
		<p>I span the full width of a small screen but a third of a medium or larger screen</p>
	</div>
	<div class="gd-12 gd-m8">
		<p>I span the full width of a small screen but two thirds of a medium or larger screen</p>
	</div>
</div>
```

## Navigation

### .hnav

Apply this to a `<ul>` element to turn it into a horizontal navigation bar. Currently does not support nested menus.

### .vnav

Apply this to a `<ul>` element to turn it into a vertical navigation bar. Currently does not support nested menus.

### .rnav

Apply this to a `<ul>` element to turn it into a responsive navigation bar. On small screens the layout will be vertical and on larger screens it will be horizontal. Currently does not support nested menus.

### Navigation example

```
<nav>
	<ul class="rnav">
		<li class="active">Home</li>
		<li><a href="/about">About Us</a></li>
		<li class="disabled">Contact</li>
	</ul>
</nav>
```


## Visability

### .hide

Hide on all screens

### .hide-s

Hide on small screens

### .hide-m

Hide on medium screens

### .hide-l

Hide on large screens

### .only-s

Show only on small screens

### .only-m

Show only on medium screens

### .only-l

Show only on large screens

### .bold-s

Make bold only on small screens

### .bold-m

Make bold only on medium screens

### .bold-l

Make bold only on large screens

## Misc utility

### .code

Give a `<pre>` a bit more flair with a `$primary-color` line down the left hand side of it.

### .collapsable

Apply this to a `<table>` element to make it collapsable.

### .disable-children-padding

Disables padding in child objects


## SCSS variables

### Queries.scss

#### $small2medium
_Default: 640_

The breakpoint for changing from small to medium sized screens in pixels.

#### $medium2large
_Default: 1024_

The breakpoint for changing from medium to large sized screens in pixels.

#### $large2xlarge
_Default: 1200_

The breakpoint for changing from large to extra large sized screens in pixels. Currently unused but considering adding xl grids in the future.

### Variables.scss

#### $font-stack
_Default: Helvetica, sans-serif;_

Our main font stack for fonts

#### $pre-font-stack
_Default: 'Courier New', Courier, monospace;_

Our font stack for `<pre>` elements

#### $dark-color
_Default: #222;_

Our primary dark color. Used by other variables below.

#### $light-color
_Default: #f2f2f2;_

Our primary light color. Used by other variables below.

#### $darker-color
_Default: #1a1a1a;_

Our complimentary dark color for dark mode.

#### $lighter-color
_Default: #fafafa;_

Our complimentary light color for light mode.

#### $primary-color
_Default: #3598E8;_

Our accent color.

#### $primary-color-text
_Default: $light-color;_

The color of text if it is within our accent color.

#### $highlight-color
_Default: #47DEFF;_

Highlight color of text when hovered over or active.

#### $disabled-color
_Default: #888888;_

The color of elements that are disabled.

#### $lightmode-fg
_Default: $dark-color;_

The foreground color in light mode. i.e. Text color

#### $lightmode-bg
_Default: $light-color;_

The background color in light mode. i.e. `<body>` background

#### $darkmode-fg
_Default: $light-color;_

The foreground color in dark mode. i.e. Text color

#### $darkmode-bg
_Default: $dark-color;_

The background color in dark mode. i.e. `<body>` background

#### $block-padding
_Default: 0.5em;_

Default padding of block elements.

## Styled elements

The following is a list HTML elements this framework explicitly styles:

- body
- h1, h2, h3, h4, h5, h6
- p
- pre
- a
- table
- td, th
- ul, li
- form
- legend
- input, select, textarea, optgroup
- option
- button
