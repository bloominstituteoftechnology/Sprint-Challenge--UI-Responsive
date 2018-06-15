<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

    The class furthest to the right has the greatest specificity. Therefore, box3 would have the highest specificity. However, if these classes were used in the cascade, the class that falls lower on the cascade has a higher specificity. 

2. Describe the difference between `display: block;` and `display: inline;`.

    `Display: block;` displays the element at the full width of the container and takes up the height of the content. No other element can be to the left or right of a block element. `Display:inline;` displays the element only for the width and height of its content.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

    `align-items: center` uses only the cross-axis. 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

    A fixed layout has fixed measurements and width and does not adapt to the screen size of the user. An adaptive layout is fixed at certain breakpoints. It relies on predefined screen sizes. A fluid layout is percent based layout. A responsive layout incorporates both fluid, adaptive, and fixed. it is considered to be the most suitable and popular design style in today's time. 

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

    Setting the max-width on the outer most container is crucial for a percent based layout. It prevents any other elements from  stretching  out of the container and contains the widths, margins, and paddings of children elements. 


