## Questions - Self Study - You can exercise your Google-Fu for this and any other _Sprint Challenge_ in the future. Remember to record your answers in _Answers.md_

1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?

<!-- <div class= "box box1 box2 box3> -->
<!-- </div> -->
Box3 will have the most speciific weight since it is the last element in the inheritance chain. 




2. Describe the difference between ```display: block;``` and ```display: inline;```.

The difference between display block and display inline will be with the way an element is layed for display. The display block will take all the space from where it is, will clear the space after it,even if it is not big enough to fill the space. WHereas inline, it will only take the space it needs and items could be sitting next to it, since it doesn't clear the space before or after it. 




3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?

The axis you use when aligning an item is the cross axis, since it streches from top to bottom. 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

the difference between each layout is with the way responds as the display medium size changes i.e. from desktop, laptop, ipad, and iphone.  

Sites that are designed with fixed layout, the width is fixed and cannot accomodate the medium change.

adaptive layout uses breakpoint which is based on viewpoint, could also be rigid. 

fluid layout, is completly dependant on viewpoint, is known to have strange effects. 

responsive layout is a combination of fluid and adaptive layout and it takes the best of those two layouts making it the best option for all medium. 


5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

The container hold container everything and items that are placed within the space abide by the container max-width.