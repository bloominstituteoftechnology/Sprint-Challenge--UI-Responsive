<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
In order of least specific to most:
	.box(_-3)
	.box .box(1-3)
	.box .box1 .box(2-3)
	.box .box1 .box2 .box3 
	
2. Describe the difference between `display: block;` and `display: inline;`.
`display: block` It lays out elements as blocks.
`display:inline` lays out elements as blocks that are "constrained" to a line.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
Unless flex-direction is specified to column it is the y axis of the Cartesian grid. In other word's the cross axis, as opposed to the main axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Fixed Layout: Set to a fixed width, content and box sizes may not change as viewport size changes.
Fluid Layout: Width, content, and box sizes chage with viewport sizes, but layout doesn't change.
Adaptive Layout: Has breakpoints which cause the layout to change depending on viewport width.
Responsive: uses percent based constraints to accomplish adaptive layout goals.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

That is the breakpoint that changes the css styling for different sized viewports.
