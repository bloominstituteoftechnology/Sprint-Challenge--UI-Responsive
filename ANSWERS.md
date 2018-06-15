<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    The class with the most weight would be box3.

2. Describe the difference between `display: block;` and `display: inline;`.
    `Display: block` browser default display, means that elements are stacked upon one another. 
    `Display: inline` means that elements will be placed juxtaposed (placed horizontally).

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    `align-items: center` is centering elements along the cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    Fixed layout: layout will remain in the same layout, ignoring of viewport size.
    Adaptive layout: layout uses fixed values and will change the layout according to preestablished viewport/device size.
    Fluid layout: uses relative values for element size and position, thus elements will change size according to viewport.
    Responsive layout: uses a combination of fluid and adaptive layouts, with the flexbox model. 

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    Max-width prevents any other width value from becoming larger than the max-width.  Important in that it provides constraints for styling predictive behavior in a layout.