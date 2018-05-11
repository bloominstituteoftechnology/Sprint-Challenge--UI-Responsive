<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
.box3

2. Describe the difference between `display: block;` and `display: inline;`.
display: block is an element that takes up the whole width of the line.
display: inline is an element that stays on the line, but the height and width does not have an effect.  (like <span>)

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
cross-axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Fixed layout is has a container that has a fixed width and the components inside have fixed width (or some percentage width) too.  It does not move when the screen is adjusted.
Fluid layout has a container that majority of its components have percentage widths.  This means that the view is adjusted for the user.
Adaptative layout means that the there are several different layouts that will adjust to the user's screen size.
Responsive layout means that no matter what device or screen size, the same layout will automatically adjust to that size.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
make it fluid and not fixed.  By adding the max-width, you can divide children elements (like width, margin l/r) to percent based.
