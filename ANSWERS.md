<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
Equal

2. Describe the difference between `display: block;` and `display: inline;`.
display: block --- block-level elements always start on a new line and take up the whole width of the line.
display: inline-block --- inline elements do not start on a new line and take up only as much width as necessary.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
Cross axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
A fixed layout does not adjust to different widths of screens and items are cut off from the page when viewed on different devices.
   An adaptive layout allows for a percentage width of the layout components. While this type of page is more user-friendly than fixed, it can get hard to view on certain devices because columns that were originally formatted for a desktop may not necessarily look good on a smaller screen.
A responsive layout adjusts content on the screen based on the different devices of users. If a user is on a website on a phone, they will see a layout that is designed to accurately fit the screen they are using.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
We need the max-width property because it allows us to make a media query applying rules for any browser width at or less than the values defined in the max-width property of said query.
