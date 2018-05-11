<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    box3 because it is the right most element in the example, thus demonstrating left-right specificity.

2. Describe the difference between `display: block;` and `display: inline;`.
    Display block displays one item per line. The items take on the dimension of a box and fill up the entire width of the space in which they are placed (unless otherwise specified). block-level items can have their dimensions changed and have padding, and margin added to their content. Inline displays it's contents on the same line as other inline contents. Inline elements have no dimensions outside of the space that their content takes up.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    The cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    The dimensions of a fixed layout stay the same regardless of viewport width. Adaptive layout's dimensions and/or layout changes based only on predefined break points. Fluid layouts adjust their dimensions to correspond to the width of the viewport, and responsive layouts combine the best features of adaptive and fluid layouts; adjusting it's dimensions based on viewport width and modifying the layout at specified breakpoints.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    In a sense this counteracts the short comings of the fluid design layout. A max width prevents the layout from expanding indefinitely with viewport width and potentially breaking as a result. 
