1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?
    .box3 would be the most specific and would overwwrite all the others if written in the CSS file below the other box classes.

2. Describe the difference between display: block; and display: inline;.
    display: block; -- items will take up the entire width of its container by defaule.
    diaplay: inline; -- items will only take up the space needed to encapsulate the content held within.

3. While using flexbox, what axis are you using when you use the property: align-items: center?
    align goes on the cross axis.
    Justify goes on the main axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    Fixed layout is hard coded, will not adjust to viewport size
    Adaptive layout is when multiple HTML files are used for different devices.
    Fluid layout will adjust the width of the content according to the width of the viewport.
    Respondive layout is a superior layout design that will incorporate adaptive and fluid layouts by adjusting the layour of the site according to the width of the viewport while using the same HTML file for all devices/users.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
    Once the layout goes over a certain width, it starts to compromise the integrity of the design.  Paragraphs become harder to read when spread too wide, images can become distorted, or can be expanded to take up entire screens.