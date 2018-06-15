<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
2. Describe the difference between `display: block;` and `display: inline;`.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
1. The box1-3 siblings would be tied for greatest specificity.
2. Block will try to take up the maximum amount of space, i.e. the whole line, and inline will try to take up the minimum, i.e. only as much as it needs.
3. Cross axis.
4. A fixed layout does not change w/r/t the viewport, an adaptive layout snaps into a new layout at specified breakpoints, a fluid layout changes continuously w/r/t the viewport, and a responsive layout is fluid up to a specified breakpoint, changes conditions and is fluid up to the next breakpoint, changes conditions and is fluid, & c.
5. Setting max-width on the outer-most element sets a constrictive boundary which will be inherited by all other elements.