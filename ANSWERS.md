<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight? 
The box3 class has the most specificity weight.
2. Describe the difference between `display: block;` and `display: inline;`.

Display: block uses elements like <div> and <p> and can have margins and padding on any/all sides.
Display: inline uses elements like <span> and <img> and can only have margins and padding on the left and right.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

Align-items uses the cross axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layout means the elements on the page do not change based on the screen size.
Fluid layouts use percentage width, so the page will change based on the screen size without squishing the content (when implemented correctly).
Responsive layouts has a different design format made specifically for each expected screen size, for example: one design for desktop, one for tablets, and one for phones.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Max-width ensures that the code will show the correct format for the screen size used. If you are viewing a site on a phone, you do not want the desktop view, so setting the max-width as 400px, for example, will load the smaller format in a responsive design. If your screen is above the 400px, it will bump up to the next format.
