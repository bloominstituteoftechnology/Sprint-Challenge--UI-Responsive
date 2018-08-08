<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

if the "box" class was selected all of them would be manipulated. and a specific number behind the word box ( box1, box2, box3) would ensure that only that single box you've selected would affected.

2. Describe the difference between `display: block;` and `display: inline;

Display: block takes the targeted element out of normal flow and positions it on it's own line that takes up full width of the page.

Display: inline positions all elements in the same parent in the same flow but cant individually be affected by width and height like block level elements

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

Align-items: center aligns all immediate children elements at the cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

A fixed layout does not resize when the viewport changes. adaptive layouts "snap" to fit predefined viewport sizes. fluid layouts allows some resizing with width percentages and can adjust to fit certain viewports. responsive layouts adjust all text, images, and spacing, and aligns itself correctly in any viewport size.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

With media queries you can change the layout of your page at different viewport sizes. Max-width ensures the containers layout is constrained when the viewport reaches a certain size.
