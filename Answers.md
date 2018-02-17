1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

In theory, box3 is the most specific, but without seeing the whole file I can't be certain.  Box is likely the least specific, but since box3 is inheriting all of the previous box styling it will probably be the most specific.  

...or, if you use all 4 selector classes - that would be really specific.  
    .box .box1 .box2 .box3{
        very: specificCSS;
    }

2.  Describe the difference between display: block; and display: inline;.

Block elements take up the entire width of their container.  A heading is a block element by default. Inline elements line up next to each other, side by side.  Imgs are inline elements by default.

3.  While using flexbox, what axis are you using when you use the property: align-items: center?

You are using the cross-axis.  By default align-items: center would move an element to the center of the vertical axis. 

4.  What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layouts only look good on the screen size(s) that they were designed for.  Fixed layouts do not respond to changes in screen size.  

Adaptive layouts are created to work at different specific screen-widths, but doesn't work well at the in-between sizes.  

Fluid layouts are more responisve than adaptive, using  % rather than px.  With fluid layouts, elements move around to fit on a screen.  

Responsive layouts use % and rem to look the best regardless of screen sizes.  

5.  Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Max-width is used for responsive websites to make sure that the content doesn't get too wide.  It constrains the data to the maximun with that the layout still looks good.  