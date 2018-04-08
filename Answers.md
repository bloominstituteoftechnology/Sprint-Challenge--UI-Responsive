1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

Class box3 has the most specificity weight because it is the last class referenced in a class tree.

2. Describe the difference between display: block; and display: inline;.

display: block is a CSS property and value that displays an element as a block level element. A block level element will start on a new line and take up the whole width of 100% by default.

display: inline is a CSS property and value that displays an element as an inline element. An inline element will not start on a new line and will take up as much space as needed. Any height height and width properties will have no effect on an element with this CSS property and value set.

3. While using flexbox, what axis are you using when you use the property: align-items: center?

You are using the cross-axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

A fixed layout website has a fixed layout that prevents the whole page from completely being viewed when the resolution is decreased to a mobile or tablet size screen. Therefore, the width of a fixed layout website cannot be changed and it is not user-friendly for website visitors who may want to view the website on a device with a lower screen size.  

A fluid layout website allows web page elements to use percentage values for measurements in order to adjust to the screen resolution of the user's device. However, developers may experience issues with their fluid layout website having too much white space if not enough content is filled on the page. Also, set widths for elements in a fluid layout website will not adjust to different resolutions.

An adaptive layout website uses a progressive enhancement technique to design websites and can adapt for various screen resolutions. However, an adaptive layout website relies on predefined screen sizes to adapt itself to resolutions for every device.

A responsive layout website is the most common design use today because it provides a precise viewing experience of a website for the user by adapting to all different size screens.

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

We need to use the CSS property max-width on the outer most container in a responsive website in order to prevent the outer most container from becoming larger when the windows of the browser is expanded and to help calculate the padding left/right and margin left/right values in percentage format for elements within the outer most container.
