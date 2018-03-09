1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
2. Describe the difference between ```display: block;``` and ```display: inline;```.
3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

1. They are all elements worth one point but I would select ```.box3```

2. A) display: block makes the element a block, creating space around it and taking up the entire width of the screen  B) display: inline puts everything on the same line inside the block you put the value on and only takes up the width it needs

3. The cross axis

4. A) A fixed layout uses hard coding and is easy to build but does not scale well on different screen sizes and has white space on larger screens. The least user friendly. B) Fluid allows for percentage widths that adjust to the screen and are white space optimized, but you must have enough content to avoid too much white space. 

4. (continued) C) Adaptive layouts fit different screen sizes using adjustable percent values that fit a wider variety of screens. You have to create multiple layouts for the different resolutions and it can slow loading times for site. D) Most recently you have the responsive layout which adapts to all devices. It loads faster than adaptive as it has one master layout. This layout must be planned well and requires longer dev testing time.

5. This max-width establishes a baseline that we set the rest of our dimension values on, so by doing this we ensure our page remains standard and optimized even on larger devices to avoid stretching. If the content is larger than the max-width, then the height will be adjusted to fit the screen better. Larger heights for smaller screens, smaller for larger, since the width allows for long lines.