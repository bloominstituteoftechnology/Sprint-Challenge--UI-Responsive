<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight? 

A: All classes have the same specificity because in HTML. Within CSS, the item the occurs most recently or at the bottom of the code will override the previous styles.

2. Describe the difference between `display: block;` and `display: inline;`.

A:   An inline element flows along with text content and won't create content to drop the the next line. Ignores top and bottom margins.

    A block element will be placed below previous elements if it needs to. It has margins and padding in every direction. Ignores vertical-align property.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

A: Cross axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

A:  Fixed layout: has a fixed width, and the components inside it have fixed or percentage widths. Will be the same width no matter what screen you use to visualize it.

    Adaptive layout: Combination between fixed and fluid layouts. Uses flex box and inline-block to adjust components.

    Fluid Layout: The components inside the container have percentage widths and will adjust to the user's screen resolution. Almost all components are adjusted using flex box.

    Responsive Layout: Responds according to the viewport the user is using. Automatically resize, hide, shrink, or enlarge, a website, to maki it look good on all devices (desktop, tablets, and phones).

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

A: To be able to have limits and break points. Works similar to an IF statements. 
