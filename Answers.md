1.  All of the classes (box box1 box2 box3) have equal specificity weight.

2.  (a) display: block will cause an element to extend the full width of the container      that it's in, and push other elements to new lines, irrespective of how much space      the element actually needs. 
    
    (b) display: inline will shorten the width of an element to only take up as much space as it needs, and enable subseqent elements within the same container to appear directly next to one another on the same line. 

3.  align-items applies to the cross-axis, which is the perpendicular axis to the           main-axis. 

4.  (a) Fixed layouts maintain the size and spacing of all the elements as they are,        irrespective of the display that the user has. Nothing changes in response to           changes in displays. 

    (b) Adaptive layouts utilize breakpoints in the css styling to change the layout based on certain display conditions. Between these breakpoints, no changes in the styling occur. 

    (c) Fluid layouts utilize percentage styling to constantly alter the styling of content on a page depending on the display condition. 

    (d) Responsive designs utilize a combination of fluid and adapative layouts, to change the layout of pages based on display breakpoints, and ensuring coherent transition between displays. 

5.  Responsive web designs use a combination of fluid and adaptive layouts -                breakpoints and percentages. Percentage layouts apply a certain percentage of a         maximum width, and the max-width property on the outermost container serves as the      maximum amount from which all other element percentages are calculated with. It         also sets a upper-limit to the display width, so that users using a larger display      won't have the content enlarging to an uncomfortable level. 