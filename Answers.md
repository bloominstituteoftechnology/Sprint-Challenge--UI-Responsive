#Assessing Your User Interface and Responsive Design Learning
---
## If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
* I would say it depends on how you call it, if we are going by structural order, ```.box3``` would have more weight. For example
```
.box {
   width: 500px;
   height: 500px;
   background: blue;
  display: inline-block;
  border: 2px solid black;
}
.box1 {
  width: 30px;
  height: 300px;
  background: green;
  display: inline-block;
  border: 2x solid black;
}
.box2 {
  width: 200px;
  height: 200px;
  background: yellow;
  display: inline-block;
  border: 2x solid black;
}
.box3 {
  width: 100px;
  height: 100px;
  background: gray;
  display: inline-block;
  border: 2x solid black;
}
```
* box3 would have the most weight, and the block would change to the specifications of ```.box3```.
---
## Describe the difference between display: block; and display: inline;.
* ```display: block``` will respect all aspects of margin, padding/ top/ bottom, but will force a line break when it comes into contact with the next element.
* ```display: inline-block``` respects all forms of margin except top/ bottom and will allow other elements to sit left/ right of it. Meaning, it does not force a line break. Multiple elements can sit in the same line as it and other (if they are also an inline-block).
---
## While using flexbox, what axis are you using when you use the property: align-items: center?
* You will be using the cross- axis, the line that runs vertically. So it will center the element in respect to where it is positioned vertically.
---
## What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
* fixed layout is exactly how it is implied. When designing, the elements keep their fixed aspects regardless of what the screen size is. Easy to develop, but on different resolutions it might not be easy to navigate.
* adaptive layout specifically adapt to the resolution you are viewing it on, easy to navigate, but to design, you'd have to design for every different resolution.
* fluid layout almost like adaptive, except content elements do not adjust according to resolution.
* responsive deisgn is complicated to design but you do not have to design to different reoslution screens, the code automatically adjusts itself to the viewing screen. It takes the best of adaptive, and fluid. But that complicates it by design.
---
## Why do we need to use the CSS property max-width on the outter most container in a responsive website?
* That is known as a breakpoint, and a breakpoints job is to ensure that from 0px - max-width px, only those specific aspects apply. Let's say that we have a screen resolution of ```2000px```, and I have a image that is also that same pixel size. If we set a container to a max width of ```1500px``` for example, then we can adjust the image size according to 1500px so that the webpage responds better. We can easily take width percentages, and the aspects can adjust accordingly to the max-width.