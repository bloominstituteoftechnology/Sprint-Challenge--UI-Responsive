1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
box3

2. Describe the difference between ```display: block;``` and ```display: inline;```.
When you use block, you're using the box-model properties and width is 100% by default, so it will fill the enitre space it is given.
When you use inline, you're still getting box-model properties, but the defaults are auto, so the elements are only as wide and high as the content. It will not expand into the entire space it is given.

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
The cross (vertical) axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Fixed layout is when all items on the page have a fixed position, which won't change no matter what screen size you view the content on (desktop, tablet, or mobile).

Adaptive layout allows for breakpoints, where the page has code that adjusts the layout at certain breakpoints (e.g., 768 or 400 px), which enables the content to be seen more optimally on certain screen sizes. Still, it doesn't accommodate all screen sizes, as the breakpoints are specifically set in the code.

Fluid layouts use relative units in the code to set things like width and height, thereby making the page capable of stretching or contracting based on the screen size/device of the user.

Responsive layouts use flexible grids, media queries, and percent based measurement to enable the layout to adapt to whatever device it is being viewed on.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

This sets the maximum width of all the content on the page. Without setting this, content may then end up shifting outside of the boundaries of the container, thereby messing up the user experience and design.
