<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    Each class has the same specificity weight.
2. Describe the difference between `display: block;` and `display: inline;`.
    Elements with display: block take up as much horizontal space as they can. Whereas, elements with display: inline take up as little horizontal space as possible while still displaying the full content that it contains.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    Align-items: center is using the cross-axis.
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    A fixed layout uses a preset page size and does not change based on browser width. Adaptive layout use fixed units like pixels but have multiple fixed widths defined by media queries.  Fluid layout uses relative units such as percentage and will fill the width of the page no matter what the width of the browser may be.  A responsive page uses both relative units and media queries as the browser increases or decreases in width a responsive layout will flex like a fluid layout, however if the browser goes beyond certain widths defined by media query breakpoints then the layout will change more dramatically to accomodate a wide or narrow width.  
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    Setting the width of block-level elements will prevent it from stretching out to the edges of its container.  However, if a browser window is smaller than the width of an element then issues can occur.  Max-width allows browser to better handle small windows.  