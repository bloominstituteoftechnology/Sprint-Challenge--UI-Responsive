<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?  
	answer: box3

2. Describe the difference between `display: block;` and `display: inline;`.
	answer:  they do the same thing except for `display: block;` adds a <br> at the end and stretches the content to all available space on the target row.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
	answer: the cross-axis (perpendicular to the main-axis).
	REFERENCE: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
	answer:
		- fixed layout:  Fixed (aka static) layout has a fixed width in pixels. The ‘container’ of the website is programmed to not move (that’s where the name ‘static’ comes from). This width stays the same independently of which screen size or resolution the viewer has.

		- adaptive layout:  Adaptive layout means that there are several versions of the layout which are displayed based on the screen size of the viewer.

		- fluid layout:  With fluid layout you specify sizes not in pixels, but in percentages. Meaning, if the screen size changes, the proportion of elements will stay the same.

		- responsive layout:  Responsive design takes the best of the two worlds of fluid and adaptive design. There are several so-called breakpoints, which divide all possible screen sizes in ranges. The interface has slightly (or completely different) layout depending on the screen size it’s viewed on. Also, depending on the screen size, elements will stretch or shrink accordingly. Responsive layout provides a custom experience for whichever screen size it’s viewed on.

	REFERENCE: https://medium.com/@space.alpaca/so-what-exactly-is-the-difference-between-fixed-fluid-adaptive-and-responsive-layouts-and-why-3773272d8481


5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
	answer:

		Use this trick and you’ll never have to worry about elements displaying too largely on an oversized monitor.
		
		div{
		width: 80%;
		max-width: 1000px;
		}
