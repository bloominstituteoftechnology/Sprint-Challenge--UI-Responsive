1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?
    box 3

2. Describe the difference between ```display: block;``` and ```display: inline;```.
    display: block
        -if no width is set, it will span to the parent container
        -can have margins and or padding;
        -if no height is set will expand to the fit the child elements
        -ignores vertical-align propert

    display: inline; 
        -flows along the content and will not clear previous content to drop to next line like block elements
        -is subject to white space
        -will ignore top and bottom margin settings but wil apply left and right margins and any padding
        -will ignore hieght and width properties
        -is subjet to vertical-align properties

3. While using flexbox, what axis are you using when you use the property: ```align-items: center```?
    align === cross axis 

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    fixed layout-
        this layout is designed to have a layout(container) that has a fixed width and the components within it also have fixed widths so that the page does not change size no matte the screen size

    adapative layout-
        this layout has several distinct layouts for multiple viewing screens 

    fluid layout-
        This layout has percetage width and adjust to the user screen 

    responsive layout-
        this layout allows web pages to render over a vairety of devices and screen sizes.

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
    We need the max-width property because it acts as a constrainer to the container to contain the page to a max width 