1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
    box3 is the most specific; anything that is changed in box3 will not affect the previous 3 boxes.

2. Describe the difference between ```display: block;``` and ```display: inline;```.
    Display: block fills the entire horizontal space with a block and stacks all proceeding blocks within the parent container on top of each other.
    Display: inline sets all the blocks within the parent container on the same horizontal plane. "inlne"

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
    Align-items: center will affect the cross axis, or y axis by default.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    Fixed layout is a layout that doesnt change no matter the width of the screen viewing the page.
    Adaptive layout is a layout that adapts based on the screen size the page is being viewed from. It's essentially a bunch of fixed layouts that are different based on size of the view screen.
    Fluid layout is a layout uses percentage widths rather than hard widths to adjust the view screen.
    Responsive layout is an adaptive layout that utilizes percentage widths to update and change dynamically based on the needs of the user; both screen size and font size.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
    To ensure there is enough room to display the html items fully and allow for dynamic updating based on the changing width of the site.