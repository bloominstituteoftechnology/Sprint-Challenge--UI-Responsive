<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
> .box3 has the most specificity. In the words of Josh Knell 'If all things are equal, the class closest to the right wins.'
2. Describe the difference between `display: block;` and `display: inline;`.
> block elements take up the entire width of the page while inline take up only the maximum amount available to their element without respect for height or width.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
> Cross Axis
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
> Fixed layouts don't change in size when the window changes. An adaptive layout has the capability to change sizes using media queries to discover how big it's screen is. Fluid layouts are completely percentage based and will always change to adapt to the current size of the screen. Responsive layouts are a mixture of media queries and relative sizes that allow a site to change to a certain extent. It is like a combination of adaptive and fluid.
5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
> when we set a max-width property on the outer most container, we are setting constraints as to how large the container will ever be. It will never be larger than the max-width.