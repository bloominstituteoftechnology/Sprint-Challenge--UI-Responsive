
1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

All 4 classes have the same amount of specificity weight.

2. Describe the difference between display: block; and display: inline;.

The biggest difference is that `display: block` will assume the entire width of its parent container, whereas `display: inline` will allow other elements to align themselves on the same line, inside the current block, only taking up as much width as they require.

3. While using flexbox, what axis are you using when you use the property: align-items: center?

The y axis. So if `flex-direction` is set to `row`, that means the items will center themselves along the vertical axis, whereas if `flex-direction` is set to column, the items center themselves along the horizontal axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layout is the old school way of making websites, and does not take into account screen size when rendering content, often resulting in the user having to scroll horizontally in order to see all the page's content.

Fluid layout means that a page's CSS properties change based on different breakpoints, allowing for more dynamic rendering.

Responsive layout means that not only do a page's CSS properties change based on different breakpoints, but that the various elements and negative space on the page scale based on the size of the screen. This is usually accomplished with proportion, for example using percentages/rems instead of a fixed number of pixels at a particular breakpoint.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

We use `max-width` on the parent container in order to make the page more readable/digestible for users/consumers. Readers (of the English language) read left-to-right, and if the text on the page is too wide, a user can easily lose their place as they move from one line to the next while reading. This is also why `line-height` is an important CSS property to consider when setting your website's type, because a larger line-height allows us to increase the text width.

