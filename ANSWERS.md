<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: 
`<div class="box box1 box2 box3"></div>` 
which class has the most specificity weight?
    box3 because it's last.

2. Describe the difference between `display: block;` and `display: inline;`.
    display: block makes all elements extend the width of the container (unless otherwise specified), so that elements are all on separate lines.
    
    display:inline makes it so that elements can be displayed next to each other on the same line

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    up-down (vertical?)

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    fixed layout- doesn't change with the screen size
    
    adaptive layout- has a different design for each screen size (it loads a different file based on screen size but is static)
    
    responsive layout- adjusts the layout of the elements to fit the browser window
    
    fluid layout- uses % to create a responsive design that flows between screen sizes

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    so that the width % knows it's a % of the container, not the body of the site.
