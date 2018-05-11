<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
Since they are all classes, they all have the same specificity of class. I believe the 'box' class would carry the most specificity weight due to source order.
2. Describe the difference between `display: block;` and `display: inline;`.
Display block elements will line up underneath the previous element and usually take up the width of the parent element. Display inline elements will line up 'in line' with the content of the parent element (if the parent is display: block), or next to another inline element on the same line. This is a key difference visually & graphically.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
The align-items property is used to describe the layout of the 'cross axis'. This is the default 'y' axis but can reference the 'x' axis if flex-direction: column is being used.
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
The shorthand difference is: Fixed & Adaptive aren't percentage based, while Adaptive uses breakpoints to 'adapt' the screen to the display of the user. Fluid & Responsive are percentage based, while Responsive uses breakpoints the same way Adaptive does, except with a fluid-like transition due to the width properties being defined in percentages.
5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
The outer most container carries all the content within it. Therefore, this is the value we need to keep track of when trying to adjust our display to the specifications of our user's browser window. If we set max-width rules for the outer container, we dont have to repeat css code due to inheritance.
