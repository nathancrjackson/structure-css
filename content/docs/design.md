---
title: "Design"
description: "An idea of why I designed some less obvious things the way that I did"
weight: 20
---

## Design

Based on things I have found when putting quick sites together I have made the following choices:

### Spacing is based on multiples of a base unit
If you check out `vars/_units.scss` you'll find variables `$x1unit` all the way up to `$x12unit`. Ideally this should mean you can edit the base `$1unit` and all the proportions scale mostly the same.

### Avoid Left/Right margin & padding on base elements
With the exception of elements like table cells and list items, pretty much everthing else has their left/right spacing set to zero. Things tend to not match up and need tweaking so I've done away with it to let container blocks handle left/right spacing uniformly.