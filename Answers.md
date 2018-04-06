1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
the class "box3" has the most specificity weight (4).

2. Describe the difference between display: block; and display: inline;.
Block level elements like <div> as welll as text blocks like <p> and <h1>
dont sit inline and take up as much space as they can (can have width and height).  Inline elements like <span> (will accept margin and padding) but not height and width.

3. While using flexbox, what axis are you using when you use the property: align-items: center?
We are using the cross axis.


4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
in a fixed layout, the widths are fixed and site doesnt move when you try to resize its window (rigid) and its not user friendly.  An adaptive layout's breakpoints are based on the viewport but can also be very rigid.  The fluid layout is 100% based on the viewport but can have different effects when resizing window.
Responsive layout is both fluid and adaptive as all window sizes are covered from mobile to desktop.


5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
We use max-width on the outter-most container to account for scrollbar and keep text readable while resizing from "mobile" size to "desktop". 
