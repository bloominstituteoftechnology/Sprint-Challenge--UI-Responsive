<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight? 

- They are all equal in weight separately, but box3 is the most specific because it's listed last and with CSS, the later the item the more precedence it takes over similar classes above it.


2. Describe the difference between `display: block;` and `display: inline;`.

- display: block; takes block level elements and gives them the entire width of the container, shifting other elements above or below.

- display: inline; uses width of element and places any other contained elements that will fit on the same line. Takes up the least space, not respecting padding.


3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

- Cross Axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

- Fixed: No matter the viewport, the width is fixed and doesn't change, cost effective.
- Adaptive: Uses break points to adjust the screen to a few or more commonly used sizes.
- Fluid: Content is full screen on all devices by using percentages to adjust for each viewport.
- Responsive: Incorporates all other layouts with percent based layouts. Max width is only on the main container.


5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

To keep some restraint on how big the website will stretch in case the site isn't programmed to that size and possibly cause issues for users.
