1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?

box3, because it is the right-most name.

2. Describe the difference between ```display: block;``` and ```display: inline;```.

A block element occupies the entire x-axis/main-axis it is positioned on, whereas an inline element does not. An inline element occupies only a space the size of the element, and can share the x-axis it's positioned on with other inline elements.

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?

cross-axis/y-axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layout is "stiff" due to its fixed width. doesn't resize for optimal viewing when the viewport expands/contracts.
Adaptive layout uses breakpoints to account for viewport resizing.
Fluid layout uses percents to account for viewport resizing.
Responsive layout combines breakpoint and percent based layouts.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

So that when percent sizes are used they are work off of the maximum width of parent containers, all the way up to outer-most.
