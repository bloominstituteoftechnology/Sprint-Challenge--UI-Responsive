<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    
    The right-most class among the siblings is the one with the most specificty weight which is box3.

2. Describe the difference between `display: block;` and `display: inline;`.
    
    `display: block;` takes up the full width of the viewport and pushes other html elements below it, an example of a block level element is a `p tag`, and `display: inline` which is represented by an `a tag` lets other elements be neighbors of it. If you want two images to be on the same row then you would use inline.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    
    `align-items: center` uses the cross axis which is vertical if the flex-direction uses the row value instead of column.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    
    A `fixed layout` uses pixels only that means it won't change if the viewport size changes which can be bad because mobile or tablet users will have a harder time navigating the size and vise-versa. An `adaptive layout` uses breakpoints in order to please other devices. Media queries allow the usage of breakpoints. If it was a desktop first approach then the developer would use max-width for the media queries and if it is a mobile first approach then the user would use min-width. A `fluid layout` uses percentages to adjust the screen. A `responsive layout` combines adaptive and flud layout by using breakpoints, rems, and percentages to make the website fully responsive.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

    `max-width` is used on the outer most container so that if the user has zoomed out very far then the site would keep expanding and that causes user error. The problem with what I mentioned is that the user would lose their attention because they have to use their peripheral vision more and other elements or sections might be skewed.