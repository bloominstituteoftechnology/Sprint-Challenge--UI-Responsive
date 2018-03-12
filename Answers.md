If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

    - Regarding classes, the Sibling Selectors have more specificity weight

Describe the difference between display: block; and display: inline;.

    - display: block behaves as a <p> block element that uses it's own new line, like a paragraph, and makes use of the full width.
    
    - display: inline behaves like a <span> and it doesn't respond to any properties regarding its width and/or height, it uses only as much width as necessary.

While using flexbox, what axis are you using when you use the property: align-items: center?

    - The cross/vertical axis is being used to center the items.

What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
    
    - Fixed layout: Static layout that uses a fixed container with the  same width disregarding which device and which resolution is being used to view the content.
    The common drawback from this method is the loss of quality of experience from the users and the necessary appearance of the "horizontal scroll" for smaller devices. As a pro it gives you full control on the way the page looks.

    - Adaptive layout: Making use of different layouts preciously prepared and written to be displayed depending on the attributes of the user's screen resolution/device. These layouts are normally activated by having a size range which contains the viewers screen size, there can be multiple layouts for multiple screen size ranges. The cons of this method is that it is time consuming and hard work is required in each of the layouts, factors that in many cases are not easily at hand. The pros of this method is providing a great user experience with fast loading times, as the server only sends the elements needed for the specific layout to be loaded.

    - Fluid layout: Percentages are used in this layout instead of fixed pixels, making every element of the page shrink or grow depending on the user's screen size on the fly, achieving a proportionality of the elements of the page. The cons of this layout is the high difficulty of designing a layout that works for small and big screen sizes, as the smallest the screen the more "crowded" the page will look and the bigger the most "blank". A pro of this method is that it is highly flexible.

    - Responsive layout: Best layout available and a combination of both the adaptive and fluid layouts. The layout will have the ability of stay proportional through screen size variations until certain "breakpoint" is reached, activating the adaptive layout prepared for the specific screen size range and making it stay proportional until the next "breakpoint" is reached activating another previously prepared layout. The cons of this layout is that much more time, work and care is needed to be completed succesfully. As a pro this layout offers the best quality user's experience being is both adaptive and fluid and is basically an expectation from users that interchangibly using desktop, tabler or phones, with an emphasis on phones as statistics show, which on themselves have a huge variety of screen sizes and pixel density.

Why do we need to use the CSS property max-width on the outter most container in a responsive website?

    - After adding the viewport, (<meta name="viewport" content="width=device-width, initial-scale=1.0">), to be able to make the website fluid by using width: 100% and changing values to be proportionate with screen size, making it adaptable by using breakpoints and creating layouts designed for screen resolutions between specific ranges, and finally making it responsive by merging both methods.