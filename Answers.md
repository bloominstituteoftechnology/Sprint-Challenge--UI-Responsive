
1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
    
    They all carry the same specificity weight. However, combining the classes in a css selector will make it more specific.
        Example: div {} is less specific than div.box1{}, div.box1{} is less specific than div.box1.box2{}, and div.box1.box2{} is less specific than div.box1.box2.box3{}


2. Describe the difference between display: block; and display: inline;
    
    An inline level element does not have top and bottom margins. It also does not have width or height. It does have padding and margins on its sides. The element is able to be displayed on the same line as other elements. By default it has an imaginary box that is as big as its content inside of it.
    
    A block level element does have height, width, and margin and padding on all four sides. By default a block level element stretches the entire width of the page and stacks on top of content that come after it in the normal flow of the document.


3. While using flexbox, what axis are you using when you use the property: align-items: center?
    
    You are using the cross axis when you use the declaration align-items: center; on an element.


4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
  
    The difference is fixed layout is what we used during the days of CSS when designers used print design as their inspiration. In print design, you have a predetermined width and height like a magazine for example. The units in a fixed layout are not relative and will remain the same on all screen sizes.

    An adaptive layout is a layout that uses media queries and changes the content based on certain breakpoints. It still utilizes fixed units to display its content.

    A fluid layout is a layout that changes the structure of elements without media queries. It uses relative units and changes the content in relation to proportions on a page.

    A responsive layout is a layout that uses media queries and relative units to display content on the page.


5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

    We need to use the max-width property on a responsive website to layout the foundation upon which we need to base our proportions on. The max width becomes the box that restrains other elements in a predetermined space. It usually stretches to the center or the edges of a viewport.