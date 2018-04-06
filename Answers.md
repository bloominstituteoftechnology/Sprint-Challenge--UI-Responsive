1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
   - box3
2. Describe the difference between `display: block;` and `display: inline;`.
   - `display: block` displays an element that starts on a new line, and takes up the entire width of the parent container.
   - `display: inline` displays an element that does not force a new line, and any height or width properties are ignored.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
   - `align-items: center` uses the cross axis.
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
   - Fixed layout: the layout does not scale or adapt to changes in viewport size
   - Adaptive layout: the layout changes at predetermined breakpoints, which are based of specific sizes of the viewport—also known as media queries. 
   - Fluid layout: the layout constantly adjusts to the size of the viewport, without the use of breakpoints, through the use of relative units.
   - Responsive layout: the layout uses both fluid and adaptive techniques, which means the use of relative units and specified breakpoints.
5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
   - The `max-width` property constrains the `width` property, because the width property uses relative units. This ensures that the layout does not expand beyond a certain dimension on very large screens, and also that the width may fill smaller screens more easily.