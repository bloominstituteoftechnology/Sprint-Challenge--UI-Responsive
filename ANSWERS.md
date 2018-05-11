<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

box3

2. Describe the difference between `display: block;` and `display: inline;`.

`display:block;` uses up all the space in the container.
`display:inline;` takes up as little space as pobbiel which can cause overlapping.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

Cross-axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

fixed layout - hardcoded with only px usage.
adaptive layout - uses px and has breakpoints which allow it to display on desktop/tablet/mobile.
fluid layout - uses %s instead of px and has no breakpoints which allows it to adjust itself based on window resolution.
responsive layout - Uses both %s and breakpoints which allow it to display itself differently based on device being desktop/tablet/mobile.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

The max-width property allows us to have a width of 100% which can be dropped down to the inhereting children to display smaller %'s.
