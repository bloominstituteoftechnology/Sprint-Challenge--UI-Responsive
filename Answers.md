1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?

The class with the most specificity weight is box box1 box2 box3, the specificity increases when there are more nested selectors.

2. Describe the difference between display: block; and display: inline;.

The difference between the two displays is that display: block takes up the whole horizontal axis causing items in this display to have its own individual lines. On other hand, display: inline; only takes up as much space as the content would allow, meaning other inline items also displayed 'inline' can appear next to it. 

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?

While using flex-box the align-items: center property will be used on the cross-axis. This is primarily indiciated by the key word 'align'. 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

A fixed layout is based on hardcoded pixels, this is going to present a horizontal scroll bar and potentially a lot of white space when the resolution of the screen changes such as when the screen is made smaller manually or by using a different device. 

An adaptive layout contains media-queries, this accounts for the size of the screen and eliminates the horizontal scroll bar by adjusting the content to fit regardless of the resolution.

Fluid layout is based on the use of percent layouts. This is for the sake of accessibility where any zoom or screen size will display the content scaled proportional to the viewing method. There is typically no media-query for this layout because it is supposed to completely scale to how the content is viewed. 

Responsive layout is typically the combination of both a percentage based layout(fluid) and media-queries(adaptive). This gives the flexibility to change the appearance of a layout based on the screen width being changed and also help scale the content based on the resolution being used.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

We need the css property max-width on the most outer container because it is used to set the content to a fixed width, every width under this container would then be done in percentage in reference to the max width declared. 
