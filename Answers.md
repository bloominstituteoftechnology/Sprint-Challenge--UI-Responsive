Self Study Questions: 

1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

	The class box3 will have the most specificity weight.

2. Describe the difference between display: block; and display: inline;

	display: block treats the element(s) it is applied to as block level elements which will take up the full width of their container.

	display: inline treats the element(s) it is applied to as inline level elements which will only take up as much space as its contents. They will stay inline with each other and wrap as needed. 

3. While using flexbox, what axis are you using when you use the property: align-items: center?

	I would be using the cross-axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

	A fixed layout has 0 responsive elements. It will be hard coded with pixels and can not respond to difference screen sizes (scrollbars will appear).

	An adaptive layout relies on predefined breakpoints to respond to different screen sizes. It uses percentages and media queries to break content and to provide a fluid experience for the user.

	A responsive layout responds to any screen size at any give width. Sites with a responsive layout will constantly resize its content with any screen changes.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

	The max-width property is needed to ensure the children of the outter most container have a reference to resize themselves to.