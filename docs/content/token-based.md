---
title: Token-based
category: Utilities
order: 1
---

## Background-color

Based on the `$feo-colors` and `$feo-themes` settings from your [design tokens](/themes), utility classes for background-color are generated. Utility classes that trigger when a pseudo-class is triggered, are also facilitated. The classes with `-ext-` can be used to add a background spanning the entire width of the screen. The following classes are available:

- `.[bg-/bg-ext-]<name>`
- `.hover:[bg-/bg-ext-]<name>`
- `.focus:[bg-/bg-ext-]<name>`
- `.active:[bg-/bg-ext-]<name>`

## Border

Based on the `$feo-colors` and `$feo-themes` settings from your [design tokens](/themes), utility classes for borders are generated. These by default provide a `1px solid` border in the corresponding color. Utility classes that trigger when a pseudo-class is triggered, are also facilitated. The following classes are available:

- `.border-<t/r/b/l>-<name>`
- `.hover:border-<t/r/b/l>-<name>`
- `.focus:border-<t/r/b/l>-<name>`

In addition, several `.border-w-<name>` are available to give borders a different width. The available sizes are 1, 2, 3, 4 and 5, which translate to `px`.

## Radius

Based on the `$feo-sizes` array from your [design tokens](/themes), utility-classes for border radius are generated. These follow the structure of `.radius-<name>`. These classes set the `border-radius` property on the element, meaning _all_ its corners.

## Margin and padding

Based on the `$feo-sizes` array from your [design tokens](/themes), utility-classes for padding and margin are generated. Next to the values from `$feo-sizes`, the 'name' `none` is also available, to overwrite standard set spacing. The following classes are available:

- `.(p/m)-<name>`: sets the padding/margin on all sides.
- `.(p/m)x-<name>`: sets the padding/margin on `-left` and `-right`.
- `.(p/m)y-<name>`: sets the padding/margin on `-top` and `bottom`.
- `.(p/m)l-<name>`: sets the padding/margin on `-left`.
- `.(p/m)r-<name>`: sets the padding/margin on `-right`.
- `.(p/m)t-<name>`: sets the padding/margin on `-top`.
- `.(p/m)b-<name>`: sets the padding/margin on `-bottom`.

## Width, min-width, max-width, `display:none` media queries

Based on the `$feo-breakpoints` settings from your [design tokens](/themes), utility classes around width are generated.

- `.w-<name>`
- `.minw-<name>`
- `.maxw-<name>` (also applies `width: 100%`)
- `.hidden-<name>` make an element hidden (`display: none !important`) above the `<name>`
- `.show-<name>` make an element hidden (`display: none !important`) below the `<name>`
- `.w-full` (sets `width: 100%`)
- `.h-full` (sets `min-height: 100vh`)
