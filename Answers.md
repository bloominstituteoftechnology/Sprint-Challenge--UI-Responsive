1) If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

The `box box1 box2 box3` class would have the most specificity weight because specificity goes from left to right.
2) Describe the difference between display: block; and display: inline;.

display: block is when something starts on a new line and takes up the entire width.
display: inline is when something does not start on a new line and takes up the least amount of space possible.

3) While using flexbox, what axis are you using when you use the property: align-items: center?

When using flexbox, align-items operates on the cross-axis.

4) What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

A fixed layout is when there are hard-coded widths that are fixed (not percentage-based).  An adaptive layout is when there are breakpoints based on viewport, but the entire layout is not viewport-based.  A fluid layout is 100% based on viewport but has no breakpoints.  A responsive layout is 100% based on viewport and has breakpoints.

5) Why do we need to use the CSS property max-width on the outter most container in a responsive website?

We need to use the CSS property max-width on the outer-most container in a responsive website because without a hard value to compare against, percentages are nigh impossible to calculate, but we can't have just a width set because that would make the layout no longer be responsive (because it would have a hard-coded width set).
