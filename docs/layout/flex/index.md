---
layout: post
id: page-flex
title: Flex
page-header:
  headline: Flex
  description: CNVS provides a number of available classes for quickly assigning flex box behavior to your layout through the use of the Flex layout toolkit. Flexbox (or "Flexible Box") provides an efficient set of styles for positioning, aligning, and distributing space among items in a container.
toc: true
---

The flex box model provides an improvement over the block model in that it does not use floats, nor do the flex container's margins collapse with the margins of its contents.  In the flex layout model, the children of a flex container can be laid out in any direction, and can "flex" their sizes, either growing to fill unused space or shrinking to avoid overflowing the parent. Both horizontal and vertical alignment of the children can be easily manipulated. Nesting of these boxes (horizontal inside vertical, or vertical inside horizontal) can be used to build layouts in two dimensions.

{% include layout/flex/flex-options.md %}
{% include layout/flex/flex-item-options.md %}
{% include layout/flex/flex-responsive.md %}