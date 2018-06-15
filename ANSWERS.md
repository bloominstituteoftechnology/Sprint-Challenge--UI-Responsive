<!-- Questions -->
1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
2. Describe the difference between `display: block;` and `display: inline;`.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?


<!-- Answers -->
1. They have the same weight, but the one lowest in terms of the cascade would have the most precedence.
2. Block takes up a whole horizontal line, while inline tries to fit in on the same line.
3. The cross axis.
4. Fixed stays the same regardless of view. Adaptive is based on breakpoints. Fluid is based on percentages. Responsive is both adaptive and fluid.
5. So as to limit the stretch of our design. Since responsive sites are also fluid, there could be trouble with especially wide pixel views (i.e. images that take up the whole page).