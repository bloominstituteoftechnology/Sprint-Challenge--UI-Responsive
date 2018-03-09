If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

	'box3' 

<!-- ==================================================== -->

Describe the difference between display: block; and display: inline;.

	inline aims to use as little room as possible. the elements will be displayed in a row, and height/width will not affect the size of the element.

	block displays elements on a new line. block elements are stacked from top to bottom, and these elements occupy the entire width.

<!-- ==================================================== -->

While using flexbox, what axis are you using when you use the property: align-items: center?

	cross-axis...
		if flex-direction = row , cross-axis = column/vertical
			the items will be centered with equal space above/below oneanother 
		if flex-direction = column , cross-axis = row/horizontal
			the items will be centered with equal space to the right/left 


<!-- ==================================================== -->

What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

	fixed layout defines elements with fixed heigh/width values. this type of layout is not user-friendly; the content of a website will typically overflow, resulting in a horizontal scrollbar.

	adaptive layouts utilize media queries to define various breakpoints in window resolution. the content of the page will usually fit a users screen without adopting a horizontal scrollbar.

	fluid layouts use percentage-based widths to fit content, which results in a more efficient way to style a webpage for various screen resolutions.

	responsive layouts are the most user-friendly, and thus, they tend to be the most difficult layout to build. a responsive webpage will fit to any screen resolution.

<!-- ==================================================== -->

Why do we need to use the CSS property max-width on the outter most container in a responsive website?

	because the children within that container will need to use a defined parent width to take advantage of percentage widths.