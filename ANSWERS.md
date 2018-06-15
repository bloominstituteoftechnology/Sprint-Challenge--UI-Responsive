<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

  box3

2. Describe the difference between `display: block;` and `display: inline;`.

  display: block; looks to put the element on it's own line, while display:inline; works to keep the element on the line, putting things on the left and right.


3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

  cross axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

  Increasingly better user experience, but also increasing difficulty in creation. Box Model

    -fixed layout: Objects are laid out with set spacing that doesn't change when browser size changes.

    -fluid layout: allows widths to be percentages, letting the page grow and shrink.
    
    -adaptive layout: introduces media queries which lets the layout be changed depending on what the size of the screen viewing it is.

    -responsive layout: combination of the above. Using percentage based widths and flexbox to keep things even and tidy, but when it reaches certain breakpoints the layout changes to fit the screen type

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

  With percentage based widths, we need a default to compare to for the targeted device. The outer most container means everything is inside it and thus ultimately referring back upwards to it.
