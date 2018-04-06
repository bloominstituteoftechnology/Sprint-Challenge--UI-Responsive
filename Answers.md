
### Question 1:
If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

### Answer:
`.box3`


### Question 2:
Describe the difference between display: block; and display: inline;.

### Answer:
`display: block;` displays an element as a block that takes up 100% of the width. `display: inline;` makes the element only take up as much space as it needs. For example, the length of the line of text. It allows multiple elements to display side-by-side;

### Question 3:
While using flexbox, what axis are you using when you use the property: align-items: center?

### Answer:
`align-items` refers to the cross axis.

### Question 4:
What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

### Answer:
* Fixed layout doesn't change at all. All font sizes and dimensions are set to pixel units.

* Adaptive layout uses media queries to set certain breakpoints and change the display depending on the screen-size.

* Fluid layout uses percentages, rem units, and/or vw/vh units to allow the elements on the page to shrink or grow depending on the screen size

* Responsive layout combines adaptive and fluid layouts to make a page that looks amazing on any screen.

### Question 5:
Why do we need to use the CSS property max-width on the outter most container in a responsive website?

### Answer:

Because if a user has a very large screen, the page will look horrible and be very difficult to read, and if the user has a very small screen, they will have to scroll horizontally to see the entire page. `max-width` allows the page to adapt to the screen size.

