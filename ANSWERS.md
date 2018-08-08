<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
- Assuming that we are comparing individual class alone (e.g. `box`), all `box box1 box2 box3` weighs the same specificity because they are counted as a class. On top of this, inside the stylesheet (`CSS`), the most bottom class (e.g. `.box3`) will overide the CSS property written above (e.g. `box`).  However, notice that specificity can be added up (e.g. `.box.box3`) and will overide the CSS property written inside lower specificity block.

2. Describe the difference between `display: block;` and `display: inline;`.
- i. `inline` take the minimum space needed to display the content. In other word, it will ignore the adjustment using `width` and `height`. On the other hand, `block` will take the `width` and `height` into account. 
- ii. `inline` will display horizontally while `block` will stack vertically.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
- `align-items` belongs to cross axis (vertically).

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
- fixed - elements are desinged in fixed pixel width and will not adjust according to the size of screen.
- fluid - elements are designed in percentage and hence, the elements will adjust according to the size of screen.
- adaptive - elements are desinged in fixed pixel but according to the size of screen, the size of elements (pixel) will change.
- responsive - a combination of fuild and adpative. The elements are designed in percentage and at the same time, the layout of elements will change according to the size of screen.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
- This allows the width of layout changing according to the size of screen, which is helpful when the screen is samll (i.e. browsing via a mobile device)
