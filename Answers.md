1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
---.box3 would carry the most weight because it is the last one in the list of siblings.

2. Describe the difference between ```display: block;``` and ```display: inline;```.
---Display: block tries to take up the entirety of available width, whereas display: inline: 'plays nice' with other elements, and generally tries to stack its horizontal real estate as close to other elements as possible, and only returns to the next line if it is necessary.

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
---We align along the cross-axis (vertically for rows, horizontally for columns).

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
-Fixed layout: nothing moves as the screen gets smaller; horizontal scroll bar appears to access off-screen content.
-Adaptive layout: changes at specific breakpoints only, otherwise, wider content has to be accessed by scroll bar.
-Fluid layout: all about proportions, and is similar to responsive in terms of element layout changing as the viewport/window is resized.
-Responsive layout: uses media queries (breakpoints) to change layouts at specific screen sizes.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
---The outer-most container holds all other content; by defining its max-width, it will prevent other child elements from overflowing past that defined boundary.