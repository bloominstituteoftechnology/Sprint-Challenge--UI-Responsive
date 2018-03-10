If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

They have the same specificity weight.


Describe the difference between display: block; and display: inline;.

If display: block is used then the item's container will fill the screen horizontally and force linebreaks before and after it. If display: inline is used then it will only take up as much horizontal space as it needs and won't force any linebreaks.


While using flexbox, what axis are you using when you use the property: align-items: center?

By default the flex-direction is row, in which case align-items moves things along the vertical axis but if flex-direction is column it moves things along the horizontal axis.


What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layouts are bad because they can't adjust to different sizes and use fixed pixel measurements.

Adaptive layouts show different versions of the site depending on various screen size cut off points.

Fluid layouts use percentages instead of pixel measurements so the screen size can change but the site will stay proportionate.

Responsive layouts are the best because they combine the advantages of adaptive and fluid layouts.



Why do we need to use the CSS property max-width on the outter most container in a responsive website?

If a max-width isn't used then everything will get stretched out when zoomed out or viewed on larger screens.