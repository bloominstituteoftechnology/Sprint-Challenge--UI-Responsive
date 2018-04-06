


If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

box3 has the most specificity weight because it inherets all the properties of the elements that come before it.

----------------------------------------------------------------

Describe the difference between display: block; and display: inline;.

A display: block; element will take up the entire space of a page whereas a display: inline; element will only take the space of it's opening and closing tags.

-----------------------------------------------------------------

While using flexbox, what axis are you using when you use the property: align-items: center?

align-items: center; will center something along the cross-axis.

-----------------------------------------------------------------

What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

A fixed layout is bordered by a clearly defined amount of space, and won't be streched, or shrunk when a browser changes it's width. Adaptive layouts will change its properties once it gets to certain breakpoints, or specfic screen sizes, and will then adjust to fit that screen. Fluid layout works similarly to adaptive layouts, but work with percentages, so they scale better. A fully responsive layout builds on fluid by resizing itself completely using relative measurements, so no matter the size of the screen, it will look neat and clean.

-----------------------------------------------------------------

Why do we need to use the CSS property max-width on the outter most container in a responsive website?

Monitors nowadays can be incredibly huge, and having the page's content fill the entire screen can be overwhelming to look at. By creating a finite border with max-width, the layout can keep a level of integrity that would otherwise be lost by streching the layout too much. 