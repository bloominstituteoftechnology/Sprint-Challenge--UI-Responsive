<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
box3 is the most specific 

2. Describe the difference between `display: block;` and `display: inline;`.

block elements take up as much width as possible, inline elements can be displayed inline side by side and take up only as much space as the box model suggests.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

Align items shifts across the major axis, so if the flexdirection is row this would be the horizontal axis, vertical if column

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

	-Fixed layouts rely on specific pixel declarations and fail to scale accross different viewports. Fixed layouts are also called static. This will likely result in a horizontal scroll bar as well.
	-fluid layouts are like fixed layouts but they use percentages as opposed to pixels, this is still not ideal as it will scale unevenly with different resolutions and even more so with aspect ratios especially. Howevever the advantage is that the relative size of the elements will be perserved when scaling.
	-adaptive layouts are essentially differet views for different devices. However it's more limited than responsive layouts because the design process works essentially from picking and choosing specific compatible devices as opposed to setting conditions that can work across a range of devices. 
	-responsive layouts are essentially both fluid and adaptive in that they rely on breakpoints that change styling conditions based on viewport sizes through the use of media queries. responsive layouts therefore, provide the most custom experience out of all the layout categories. These typically rely on rem scaling for accessibility as well.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
	If there were no max width you would be helpless in accepting whatever large desktop view a user was using. Setting a max-width helps to fix all of the other elements in proportion to one largest element, which can be considered the fluid aspect of responsive layouts. 


