<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

box 3


2. Describe the difference between `display: block;` and `display: inline;`.

display:block allows you to put content in a box with a specified length and width (and margins/padding). The box your element in takes up the whole line (as opposed to display: inline-block)

display:inline makes it so that your element is placed in a box sized so that the element has no margins and padding. Also, display inline doesn't take up the whole line like display:block.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

cross-axis 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

fixed layout: content size doesn't change based on the device screen size 

adaptive layout: content changes for specific device screen size only at breakpoints

fluid layout: content scales to whatever device screen size you are using. No breakpoints or different views depending on screensize. 

responsive layout: Similar to fluid layout in that it scales depending on your screen size, but different in that it has breakpoints that can change the way your content is structured to make it more appropriate for different devices. 

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Because otherwise the content in the container will be too wide for comfortable viewing on a desktop.
