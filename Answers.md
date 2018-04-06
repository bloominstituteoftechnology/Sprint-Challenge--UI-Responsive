
#If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight#

.box box1 box2 box3

#Describe the difference between display: block; and display: inline;.#

Block spreads up the available space with a new line. No other element is allowed in block.

Inline takes up space as it needs, and doesnt jump to a new line. 

#While using flexbox, what axis are you using when you use the property: align-items: center?#

cross axle


#What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?#

Fixed layout doesn't change as the browser size changes. Might work fin on static desktop views but diastrous views on smaller devices.

Adaptive layout uses media queries to adjust to different widths. Still uses pixels but with media queries, it is able adjust.

Liquid layout, uses percentages and ems or rems versus pixels, makes it more flexible aka fluid. 

Responsive layout uses both relative units like rems &percentages and media queries. Usually mobile first layouts uses responsive design because if browser goes beyind certain sizes, the lay out might change big time.

#Why do we need to use the CSS property max-width on the outter most container in a responsive website?#

As there are many different devices with various sizes these days, having max-width set to a certain pixels improves browser's adjust smaller devices. For very wide screens, if max-width is larger than the screen size, the content might take full screen or vice versa.