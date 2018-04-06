## Questions - Self Study - You can exercise your Google-Fu for this and any other _Sprint Challenge_ in the future. Remember to record your answers in _Answers.md_

1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
    Each of the classes are equally weighted. The class that's declared furthest to the right in the CSS file will take precedence. 

2. Describe the difference between ```display: block;``` and ```display: inline;```.
    display: block:
        - element starts on a new line and takes up the full width of the page 
        - doesn't allow any other elements to next to it.
        - has some whitespace all around it.
    display: inline: 
        - element is displayed on the current block or same line.
        - element only takes up enough width as necesary.

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
    Align = Cross Axis
    Justify = Main Axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

    fixed layout: 
        -Layout is fixed. Meaning that the elements on the page do not move with different screen sizes (resolutions). Not user friendly.

    Adaptive layout:
        - Adapts itself to fit into differnt screen resolutions. Adaptive web design relies on predefined screen sizes to adapt itself to resolutions across devices.


    fluid layout:
        -This uses percentage width for the layout of the web page. In theory this allows the page layout to adjust to users different screen sizes.

    responsive layout: 
        -Is designed specifically to adapt the layout to account for differenct screen sizes. i.e. desktop, tablet, phone.
        -Responsive page loads faster than adaptive page because.
        -Leverages media queries to accomplish this.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
        -To place nice with the media queries. It acts like a boudary. 
        -To maintain the page layout's integrity irrespective of the screen size a user has.