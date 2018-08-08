<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
2. Describe the difference between `display: block;` and `display: inline;`.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

ANSWERS:

1. Box, box1, box2, and box3 all have the same specificity weight. In terms of CSS, which ever class is last referenced will take precedence over the other classes.

2. Display: block will show the elements stacked on top of each other. Display: inline will show the elements in a single line (given the space is not restricted and has enough room to accommodate all elements listed).

3. Main axis.

4. 	Fixed: Screen size does not affect content. The content will bleed into the invisible space. Not very user/device friendly.
	Adaptive: Content layout will adjust according to screen sizes. However, designer will need to create multiple layouts (CSS) to accommodate the different screen sizes.
	Fluid: Content are percentage based, making the design/content more user/device friendly. However, poses certain challenges as the percentage may alter the original design.
	Responsive: Most popular layout in modern times, given the variety of users and screen sizes. The content will automatically adjust itself based on the designer's master layout.

5. Max-width will help the designer to exert control on the page and limit the change to only the height on the device. 
