<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
Answer: box3

2. Describe the difference between `display: block;` and `display: inline;`.
Answer: display: block occupies the entire width of the line the element is placed on. It does not let other elements occupy the same line. If there are other elements on the same line they will be pushed below to a new line. 

example: <p>Hello</p>
css file
p{
  display: block;
}

p is an inline element by default, when display: block is applied to p it will occupy the entire width of the screen and will not let other elements stay next to it.

display: inline when applied to an html element will let other elements stay to the left or right of the element. 

example: <div>Hello</div>   //Hello
        <div>World</div>     //World
        
css file
div{
  display: inline-block;     //Hello World
}

div is a block element by default, when display: inline-block has been applied to the divs, they will be converted to inline-elements and the 2 divs will stay next to each other on the same line.


3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
Answer: Cross Axis


4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Answer: fixed layout: Fixed layout doesn not change according to the screen size or resolution. It has no break points and no %. It has a fixed design.

adaptive layout: The  design changes according to different screen sizes but does not have % based widths. It is tedious since different layouts need to be created for different screen sizes. 

fluid layout: all % based and no break points. The design changes due to the % based widths and adjusts to different screen resolutions. 

responsive layout: There is just one layout unlike adaptive and as a result it loads faster. It has % based + breakpoints to adjust to different screen sizes.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
Answer: max-width is to make sure that the container does not exceed the max-width we assign it. If max-width is 880, it makes sure that if the screen size increases and goes beyond 880 the container still retains 880 as it's width. max-width has no effect if the screen is smaller than max-width.   
