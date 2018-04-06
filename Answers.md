If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
    .box3

Describe the difference between display: block; and display: inline;.
    display: block; uses the entire span of the width.  This causes the next element to be below it.
    display: inline; makes the element take as little space as it can.  This makes it so items will get bunched into one line.

While using flexbox, what axis are you using when you use the property: align-items: center?
    align-items: center; affects the cross axis.  

What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    fixed layout - the displayed content is the same no matter where you view it.  It's easy to design, but not accessible by everyone who uses it.
    adaptive layout - you hard code different versions and the server will see what device you are using and display the appropriate content.
    fluid layout - using percentages and REM, you can change the size of content displayed so that it will fit your viewport without having to scroll.
    responsive layout - using media queries and flexbox, we are able to set breakpoints that change the way the content is rendered at different sizes.

Why do we need to use the CSS property max-width on the outter most container in a responsive website?
        if you do not have a max width in a responsive website, when rendering on a extremely wide or large screen, your webpage will be distorted
    depending on how you have set it.  Example, if you used percentages, your page will be very large.  Or if you used justify-content: space-between,
    you will have a lot of white space.