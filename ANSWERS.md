<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
Answer: box3
2. Describe the difference between `display: block;` and `display: inline;`.
Answer: 'display: block;' stretches the frame around the element across the entire horisontal axis and does not allow other elements on the same row. Block elemets can not have defined width.
'dispaly: inline' on the other hand only takes as much space as the element inside it and any other inline elements after it stick next to the element on the same axis, as long as they fit on the same row. Inline elements can have defined width. 
3. While using flexbox, what axis are you using when you use the property: `align-items: center`? 
Amswer: vertical axis
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
Answer:
FIXED: no breakpoints, no % based layout
ADAPTIVE:  breakpoints but no % based layout
FLUID: all % based, but no breakpoints
RESPONSIVE:  breakpoints + % based layouts

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

ANswer: So that we can control the layout design in accordance with the maximum with of the device which it is viewed on. Max-with is needed when the initial layout is designed for larger screens, such as desctops and needs to be adapted to be viewed on smaller screens. If the intial design is meant for smaller screens, such as smart phones, then min-with is the property that helps establish a breakpoint for larger screens. 
