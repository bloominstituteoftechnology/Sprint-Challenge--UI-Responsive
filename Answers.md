1.  If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

They all have the same specifity. If you select it like so: '.box.box1.box2.box3' then it's the most specific.

2.  Describe the difference between display: block; and display: inline;.

Blocks become their own space with padding and usually on a new line. Inline will
create a an item on the same line with parent's constraints.

3.  While using flexbox, what axis are you using when you use the property: align-items: center?
    If the current direction is row, it will center vertically.

4.  What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layout will not respond to smaller screens. Adaptive changes at specific widths.
Fluid layout will change as you lower the width. And responsive is the the layout of the
site changing altogether at different sizes.

5.  Why do we need to use the CSS property max-width on the outter most container in a responsive website?

So that anything done inside can't be bigger the the size of the screen.
