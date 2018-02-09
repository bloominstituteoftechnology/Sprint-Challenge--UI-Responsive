## Questions - Self Study - You can exercise your Google-Fu for this and any other _Sprint Challenge_ in the future. Remember to record your answers in _Answers.md_

1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
        box 3

2. Describe the difference between ```display: block;``` and ```display: inline;```.
    ```display: inline`` is the default property for css. Items are displayed inline; height and width dimensions have no impact on it.
    ```display: block``` displays each element as a block on a new line. These blocks take up the entire width.

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
    vertical

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    A fixed layout is static, it does not adjust for viewport dimensions.
    A fluid layout contains fixed elements whose dimensions are based on a percent of the viewport size.
    An adaptive layout adjusts to the viewport. This is done through creating different layouts based on viewport size.
    A reponsive layout uses one master layout that repositions elements based on the viewport size.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
    So we our elements can have dimensions based on the percentage of max-width, allowing for more responsiveness. Otherwise, they would have fixed widths, which only look good in specific viewports.