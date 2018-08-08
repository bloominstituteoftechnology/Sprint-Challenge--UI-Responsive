<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

Based on only the HTML, it would be box3, but it would really depend on the CSS ordering of the classes. If box would come after box1, box2, and box3 in the CSS, it would have the most specificity, so we must be careful with the ordering of our CSS class naming.

2. Describe the difference between `display: block;` and `display: inline;`.

I think of block as an actual block, where a big block is utilized for the space contained in the website. It tends to take up width if the width is not defined, which sends the next item to the next line. Inline elements don't have a defined width + height, and allows for elements to be next to them.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

Cross Axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed: Has a fixed width. If you change the dimensions in any way, a scroll bar will pop up and the website will be in the pixels the website was designed in.

Adaptive: Designed to fit into different screen sizes. The designer builds different layouts for different screen sizes.

Fluid: The widths are now defined in %s, which allow for a better experience. However, at really small widths, this can lead to really thin columns, which may look disgusting.

Responsive: A fully responsive experience, where the website adapts to the screen sizes of the users.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

We use the max-width because, i.e. someone is looking on their phone, we don't want a width of 880px. Also, because we're using a % for the width now, we don't want an ugly stretch when someone is using a bigger width for what we designed (let's say 880px width). For example, my browser is 1980 x 1024, so if the width was 100% without max-width, the stretch could cause some ugly content!