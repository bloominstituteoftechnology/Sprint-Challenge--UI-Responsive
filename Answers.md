## Questions - Self Study - You can exercise your Google-Fu for this and any other _Sprint Challenge_ in the future. Remember to record your answers in _Answers.md_

1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
    a. There are several combination for the ```<div>``` element. The mos specific is the one that comibne all classes: ```div.box.box1.box2.box3.box4```
2. Describe the difference between ```display: block;``` and ```display: inline;```.
    a. ```display: inline`` => occupies only the necessary space along its x-axis (parent width).
    b. ```display: block``` => occupies all the space along the x-axis (parent width).
3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
    a. cross-axis.
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    a. **Fixed**: Layout is fixed and does not change at viewport change.
    b. **Fluid**: Layout design is fixed (elements do not change its relative position to others elements), but content 'adapt' in order to 'fit' within the viewport.
    c. **Adaptive**: Files are served to browser according to specific rules based on device properties. In other words, Layout is tailored to specific 'browser properties'.
    d. **Responsive**: Layout design adapts to several viewports. Elements relative position to others elements may vary.
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    a. This allows us to set 'relative' sizes for elements properties in percentages, so the layout scales according to viewport dimension.