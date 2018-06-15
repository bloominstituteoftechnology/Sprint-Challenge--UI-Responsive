<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
Answer: each class would have an inherently identical specificity value of 10, so if, for example, the same property (say `background:`) were set to different values within each class, then the value within the class __lowest in the code__ would take precedence.

2. Describe the difference between `display: block;` and `display: inline;`.

Answer: an element set to `display: block;` will span the entirety of the the container it is in, while an element set to `display: inline;` will take up only as much space as its content, so it will not start on a new line as it were. Of the most commonly used elements, `<img>`, `<span>`, and `<a>` are inline, while most everything else is block. 

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
