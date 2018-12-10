<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

Each name shares the same specificity. The one that is read last in the css sheet will be rendered.

2. Describe the difference between `display: block;` and `display: inline;`. 

Block uses a full line for the element and without "Float" it cannot be horizontally next to another element.
Inline displays the element in the same line as the elements nearest to it so long as space permits, it does not necessarily create whitespace above and below.


3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

You are using the cross axis. 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layouts are pages with elements that maintain a specified size regardless of the device viewing them. The page will not
conform to the screen size of the viewing device and will remain static. Adaptive layouts are use fixed units, but have media query breakpoints
for more adaptability.

Fluid layouts are responsive to a fault. They are entirely based on the screen size of the device, and will size themselves to fit the width of the device always, which
can be problematic given a device too small or too large.
Responsive design layouts are layouts that are fluid, but have specific breakpoints which tell it when to stop shrinking or stop growing.
Responsive layouts are scalable to a perfection.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

The max-width property on the outermost container tells the page to change its appearance at the specific breakpoint, it also
keeps the content stretching too far as it would on a fluid layout.
