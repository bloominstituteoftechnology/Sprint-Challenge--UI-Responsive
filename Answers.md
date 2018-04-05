## Questions - Self Study - You can exercise your Google-Fu for this and any other _Sprint Challenge_ in the future. Remember to record your answers in _Answers.md_

1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?

    In this example, they are equal because they are all separate classes unto themselves.

2. Describe the difference between ```display: block;``` and ```display: inline;```.
       Display-block will span the entire width of the parent container.  Display-inline will only use however much space is needed to display the items correctly.
       
3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?

    Items will be centered on the cross axis.


4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    Fixed-layout will not change no matter what type of device is being used to access the site.

    Adaptive layout uses breakpoint to specify changes to the look and/or layout of the site when certain breakpoints in the size of the viewport are hit, for example if the viewport is 768px or below, a new layout would kick in to make the site more viewable on a smaller screen. 

    Fluid layout is based upon the device that is being used to view the site.

    responsive layout uses both fliud and adaptive principles mainly based upon percentages of the parent elements to resize content and/or change the layout based upon the size of the viewport. 

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

        The max-width property is used on the outer-most container because the rest of the elements inside the container will determine their size based upon a percentage of the total size of the parent container.  When te viewport size changes, the outer container resizes and the child elements inside of the parent contasiner will resize as well based upon the percentage of the parent container.