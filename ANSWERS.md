<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
    `box3`

2. Describe the difference between `display: block;` and `display: inline;`.
    `display: block;` will format an item so that it holds its own ground irrespective of the spans parameters. This means the item will stack and will "push against" the other items around it. `display: inline;` will cause the item to act more like text, in that it will literally fall inline with the other items near it, causing a row. 

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
    Cross-Axis

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    Fixed Layout:
        A fixed layout is a web page with static width, and in some cases height, used primarily for desktop viewports. It's advantage is that it is straightforward and easier to build. Disadvantage is that it doesn't adapt at all to alt devices, such as tablets and mobile. 
    Adaptive Layout: 
        An adapative layout is a web page with functionality at fixed widths, known as breakpoints, typically being 1000px for Desktop, 768px for Tablets, and 400px for Mobile. Like fluid, the advantage is that the page will be adapative to a wider set of media devices. However, it remains a rigid format in that it isn't fluid and additionally requires the developer to custom-tailor content to these preset designs.  
    Fluid Layout: 
        A fluid layout is a web page with percentage widths, which means the items on the page are responsive to the browser's viewport shrinking in width beyond the width of the page contents. The advantage to this is that it is more adaptive to a wider user base, however, it requires more thought on the front end for the developer to account for how movement of items on the page will affect the content. 
    Responsive Layout: 
        A responsive layout is currently the most ideal of web page formats, in that it incorporates the percentage based widths of a fluid layout along with the breakpoints of an adapative layout. It's disadvantage is that, in accounting for the best of both worlds, it requires further developement time. 

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
    Without the CSS propery max-width on the outer most container, the page will introduce a scroll bar if the viewport gets to be smaller than the width of the page's content, rather than rearanging/shrinking the content to fit within the smaller viewport size. 
