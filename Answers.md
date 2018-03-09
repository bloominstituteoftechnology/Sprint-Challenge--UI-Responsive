1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
box3 I believe. It's the last in order and specificity cascades over and, when not nested, gives greatest weigt to the last item. 

2. Describe the difference between display: block; and display: inline;.
Block is vertical and inline is horizontal.

3. While using flexbox, what axis are you using when you use the property: align-items: center?
Align goes along the cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Fixed layout is fixed in terms of size and does not respond well to changing viewport sizes. Easier to manage and make.
Adaptive layout has media queries and adapts at specified sizes.
Fluid layout maintain the integrity of the design at all sizes. % based. Page looks the same on a phone or computer.
Responsive layout is completely % based with media queries that allow for different designs at specified sizes.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
Setting the max-width helps maintain the intended size when a screen size exceeds the max width.
