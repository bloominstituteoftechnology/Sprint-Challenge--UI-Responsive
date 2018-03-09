1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
Can't tell.  Need to see actual class style sheet.

2. Describe the difference between display: block; and display: inline;.
Display block defines a boxes that stack one on top of each other.
Inline defines boxes that stack side to side.

3. While using flexbox, what axis are you using when you use the property: align-items: center?
Cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Fixed:  The layout, all widths, margins, padding, etc. do not change with screen size.  If the screen is too small, things just get cut off. If too big, then white space.

Fluid: Widths are defined in percentages so the layout and content squeezes or stretches according to screen size.

Adaptive:  Site adjusts based on specific pixel width break points 

Responsive:  Site adjusts smoothly as the screen size changes. 

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

So we can have a root width to divide with to calculate child element widths.
