1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` 
which class has the most specificity weight? box3, furthest right 
Specificity is a weight that is applied to a given CSS declaration, determined by the number of each selector type in the matching selector. When multiple declarations have equal specificity, the last declaration found in the CSS is applied to the element. Specificity only applies when the same element is targeted by multiple declarations. As per CSS rules, directly targeted elements will always take precedence over rules which an element inherits from its ancestor.

2. Describe the difference between ```display: block;``` and ```display: inline;```.display: block means that the element is displayed as a block, as paragraphs and headers have always been. A block has some whitespace above and below it and tolerates no HTML elements next to it, except when ordered otherwise (by adding a float declaration to another element, for instance).

display: inline means that the element is displayed inline, inside the current block on the same line. Only when it's between two blocks does the element form an 'anonymous block', that however has the smallest possible width.

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?The CSS align-items property defines how the browser distributes space between and around flex items along the cross-axis of their container. 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
A fixed website has a fixed layout and the components have to come inside it. The layout does not move in this option. The width of the layout does not change the screen resolution. This sort of a website layout is not user-friendly for the visitors as it does not adapt to the screen size of the device they are using.

A fluid design allows percentage width of the layout components. These components adjust to the screen resolution of the user. The designer can also keep certain elements as fixed, even in this kind of a design.

Fixed websites have a set width, and resizing the browser or viewing it on different devices won’t affect on the way the website looks. This can require horizontal scrolling and a site that doesn’t look good on tablets or smartphones.

Fluid websites are built using percentages for widths. As a result, columns are relative to one another and the browser, allowing it to scale up and down fluidly.

Adaptive websites introduce media queries to target specific device sizes, like smaller monitors, tablets, and mobile.

Responsive websites are built on a fluid grid and use media queries to control the design and its content as it scales down or up with the browser or device.
2. A Fluid Website Design

Fluid: websites are built using percentages for widths. The concept of fluid design was being used way before Ethon Marcotte coined the term “responsive design.” It’s pretty safe to say, that fluid design evolved into responsive design.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?Containers are the most basic layout element in Bootstrap and are required when using our default grid system. Choose from a responsive, fixed-width container (meaning its max-width changes at each breakpoint) or fluid-width (meaning it’s 100% wide all the time).

While containers can be nested, most layouts do not require a nested container.

