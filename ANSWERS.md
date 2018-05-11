<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    
    .box3

2. Describe the difference between `display: block;` and `display: inline;`.

    p tags are block level elements. If given a border, and no other css, it will go across the width of the page.
    The same is true of headers (h2, etc.), lists (ul, etc.), and divs.

    a tags are inline elements. They’ll wrap around themselves and not go wider. The same is true of <button>, <span>, and <img>.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

    cross-axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

    Fixed = no breakpoints, no % based layout - looks like crap because it’ll be cut off on both sides.
    Adaptive = breakpoints but no % based layout - manipulating CSS to look different on mobile.
    Fluid = all % based, but no breakpoints - it can go TOO wide, for example, http://getbootstrap.com/.
    Responsive = Breakpoints + % based layouts

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

    so that we can make % calculations for inner container widths, margins, etc. and so that we can create media queries at certain breakpoints