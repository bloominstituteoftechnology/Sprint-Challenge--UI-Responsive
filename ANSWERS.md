<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
  1. Answer - box3

2. Describe the difference between `display: block;` and `display: inline;`.
  2. Answer - 'display: block;' is like stacking children's blocks on top of one another, they default to vertical orientation.
            - 'display: inline;' puts the blocks horizontally next to each other, but not necessarily respecting the vertical axis.
            - dispaly: inline-block;' combines the two and puts the blocks inline (side by side) and respecting the vertical stacking.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
  3. Answer - cross axis if set to rows.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
  4. Answer - In a fixed layout, all objects are set to a specified width, user will have to scroll to view contents.
            - In an adaptive layout, the objects are set to different design specifications depending on the max width.
            - In a fluid layout, the objects will adjust width to fit the devise but the layout will not change like an adaptive layout.
            - In a responsive layout, the objects will be fluid and the layout will change depending on the device or size of page.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
  5. Answer - We need to use the max-width property to set an outer limit on out webpage. If no outer limit is set than everything would
              expand beyond normal viewing resolutions and would not look good on wide screens. It is also essential so that child elements
              have a constraint.
              
