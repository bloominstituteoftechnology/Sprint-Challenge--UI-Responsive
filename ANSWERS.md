<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

Box 3

2. Describe the difference between `display: block;` and `display: inline;`.

Block-elements take up all the space on a page (if a set height or width is not defined), while inline elements align themselves with the elements around them if not otherwise specified.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

cross-axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layouts do not compromise their layout no matter the viewport size.
Adaptive layouts adjust their layout within speicifed viewport sizes. More tedious as it requires templates for each screen size.
Fluid layouts use a percentage-base approach on items' widths to allow for a fluid change in layout as viewport sizes change.
Responsice Layouts allows for a website to adjust its layout accordingly for all types of devices.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

This will prevent our website from expanding infinitely into an un-viewable size. It also gives us a reference point for all other elements inside the container to be manipulated within.