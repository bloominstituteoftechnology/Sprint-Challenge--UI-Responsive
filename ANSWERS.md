<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

Wouldn't it depend on what gets defined last in the CSS?  Presumably box3 would have the most specificity if you were writing the CSS in numerical order.

2. Describe the difference between `display: block;` and `display: inline;`.

`display:block` is verticle, `display: inline` is horizontal.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

The cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed: This layout remains the same accross differing viewports.
Adaptive: This layout uses media querries for viewport break points.
Fluid: This layout uses percent based sizing of items to resize content as the viewport expands and contracts.
Responsive: This layout combines the percent based sizing of a fluid layout and the media querries of the adaptive layout.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

So that the content doesn't continue to expand indefinitely as the viewport expands.
