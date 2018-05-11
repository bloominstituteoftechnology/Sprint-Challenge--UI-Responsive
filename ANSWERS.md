<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
   All of those classes have the same specificity weight, but box 3 should override the other classes (from left to right specificity).
2. Describe the difference between `display: block;` and `display: inline;`.
display: block automatically takes up the full span of its parent elements width, inline allows for multiple elements to reside on the same level.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
cross-axis
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Fixed layout has one constraint, and all items are placed by that constraint, horizontal scroll bars activate when the window is resized, and nothing changes dimension.
Adaptive Layout has fixed media query breakpoints that target specific devices, and allows for content to snap to different dimensions as the viewport or window is resized.
Fluid layout is built using percentage widths so that items resize based on the window.
Responsive layout is built with media queries that target general sizes, and scales images, wraps text and adjusts based on the viewport size to provide the optimal view across many devices.
5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
to constrain the size of our desktop view, so everything isn't fluid on really high resolution monitors, tvs etc.
