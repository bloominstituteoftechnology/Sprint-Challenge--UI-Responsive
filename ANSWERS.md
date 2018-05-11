<!-- Answers to the Self Study Questions go here -->


1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

	a. Depend on where it is being called in the CSS file and how much weight/specificity is being called.

2. Describe the difference between `display: block;` and `display: inline;`.

	b. display: block takes up the whole block for that element while display: inline only take up the minimal possible width.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

	c.the cross axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

	d. Fixed Layout: Rigid, will not change on different platform.
	   Adaptive Layout: Has different layout for different viewport size.
	   Fluid Layout: Will stretch or push in to fit the screen size.
	   Responsive Layout: Is a combination of an Adaptive layout with Fluid layout,
	   currently the standard for current industry.
	
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

	e. Without it, it’s just an another fluid layout, the max-width will force the page layout to adjust accordingly to the CSS you set inside the media query of that max-width.
