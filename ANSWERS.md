<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
	box3 would be most specific
2. Describe the difference between `display: block;` and `display: inline;`.
	inline doesn't break the flow of text, such as a <a><em><span> tag.
	block break past inline and take up as much horizontal space as they can,for example, <div><p><section>
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
	Cross axis
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
	*Fixed: Widths are fixed and sites don’t budge. Very rigid.
	*Fluid: 100% based on the viewport but can have strange effects at different sizes
	*Adaptive: Breakpoint based on viewport but also very rigid.
	*Responsive: Fluid + Adaptive = all bases covered from phone to desktop.
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
	Because it will stretch across the screen taking up 100% of the viewport.