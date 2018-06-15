<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    * Answer: each class would have an inherently identical specificity value of 10, so if, for example, the same property (say `background:`) were set to different values within each class, then the value within the class __lowest in the code__ would take precedence.

2. Describe the difference between `display: block;` and `display: inline;`.

    * Answer: an element set to `display: block;` will span the entirety of the the container it is in, while an element set to `display: inline;` will take up only as much space as its content, so it will not start on a new line as it were. Of the most commonly used elements, `<img>`, `<span>`, and `<a>` are inline, while most everything else is block. 

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

    * Answer: `align-items:` pertains to the cross axis, while `justify-content` pertains to the main axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

    * Answer: 
        * fixed layout websites have fixed widths such that the layout does not adapt to the user's screen size.
        * fluid layout websites adjust to the size of the user's viewport but has some issues for the user at different viewport sizes (for example, items with fixed widths such as images cannot be set to fit the viewport size in question)
        * adaptive layouts are based on breakpoints but you have to make multiple distinct layouts to fit each viewport size. 
        * responsive layouts combine the best of both worlds of fluid and adaptive layouts, using media queries to respond to any viewport size and avoid having to create different layouts for each one.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    * Answer: a max-width set on the outmost container for the content is an absolute necessity for fully-responsive layouts because this, in tandem with percentage-based widths, is what allows for the content to adjust to the viewport size.
