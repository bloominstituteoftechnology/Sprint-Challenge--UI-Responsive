<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

Class box3 has the most specificity weight.

2. Describe the difference between `display: block;` and `display: inline;`.

`display: inline;` presents elements as if they naturally flow side-by-side, like phrases in a word processing document. `display: block;` on the other hand will cause elements to break from each other; they will no longer exist on the same "line."

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

You are using the cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layout involves rigid pixel dimensions, regardless of display.
Adaptive layout involves different fixed layouts across specific breakpoints.
Fluid layout involves the use of percentages so that the layout changes according to every device width.
Responsive layout is a combination of adaptive and fluid layout principles, so that certain "tentpole" breakpoints are presented with adaptive layouts, and percentages handle the displays that fall in between.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

The max-width property allows us to create layouts according to various breakpoints, while also accommodating for device widths that fall in between those breakpoints. We position and size the interior page elements accoring to this max-width value as design benchmarks.
