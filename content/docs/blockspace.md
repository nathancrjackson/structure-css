---
title: "Block space utilities"
description: "Utility classes to manage padding and margins easier"
weight: 90
---

## Classes

### .align-center

Try center a block within another element.

### .m-x{num}

Have a margin evenly around an element that is _{num}_ times the base `$1unit`.

### .m{x}-x{num}

Have a margin for an element where _{x}_ is the direction and is _{num}_ times the base `$1unit`. Here is a table with examples when the num is 1:

|   | Left | Right | Top | Bottom | X-axis | Y-axis |
|---|---|---|---|---|---|---|
| _1_ | ml-x1 | mr-x1 | mt-x1 | mb-x1 | mx-x1 | my-x1 |

### .m-auto

Have a margin around an element that is set to `auto`.

### .m{x}-auto

Have a margin for an element that is set to `auto` where _{x}_ is the direction. Here is a table with all of the options:

| Left | Right | Top | Bottom | X-axis | Y-axis |
|---|---|---|---|---|---|
| ml-auto | mr-auto | mt-auto | mb-auto | mx-auto | my-auto |

### .no-m

Disable margin for an element (i.e: set to 0 and mark !important).

### .no-c-m

Disable margin for children of an element (i.e: set to 0 and mark !important).

### .no-m{x}

Disable margin for an element where _{x}_ is the direction (i.e: set to 0 and mark !important). Here is a table with all of the options:

| Left | Right | Top | Bottom | X-axis | Y-axis |
|---|---|---|---|---|---|
| no-ml | no-mr | no-mt | no-mb | no-mx | no-my |

### .no-c-m{x}

Disable margin for children of an element where _{x}_ is the direction (i.e: set to 0 and mark !important). Here is a table with all of the options:

| Left | Right | Top | Bottom | X-axis | Y-axis |
|---|---|---|---|---|---|
| no-c-ml | no-c-mr | no-c-mt | no-c-mb | no-c-mx | no-c-my |

### .p-x{num}

Have an even padding in the element that is _{num}_ times the base `$1unit`.

### .p{x}-x{num}

Have padding for an element where _{x}_ is the direction and is _{num}_ times the base `$1unit`. Here is a table with examples when the num is 1:

|   | Left | Right | Top | Bottom | X-axis | Y-axis |
|---|---|---|---|---|---|---|
| _1_ | pl-x1 | pr-x1 | pt-x1 | pb-x1 | px-x1 | py-x1 |

### .no-p

Disable padding for an element (i.e: set to 0 and mark !important).

### .no-c-p

Disable padding for children of an element (i.e: set to 0 and mark !important).

### .no-p{x}

Disable padding for an element where _{x}_ is the direction (i.e: set to 0 and mark !important). Here is a table with all of the options:

| Left | Right | Top | Bottom | X-axis | Y-axis |
|---|---|---|---|---|---|
| no-pl | no-pr | no-pt | no-pb | no-px | no-py |

### .no-c-p{x}

Disable padding for children of an element where _{x}_ is the direction (i.e: set to 0 and mark !important). Here is a table with all of the options:

| Left | Right | Top | Bottom | X-axis | Y-axis |
|---|---|---|---|---|---|
| no-c-pl | no-c-pr | no-c-pt | no-c-pb | no-c-px | no-c-py |
