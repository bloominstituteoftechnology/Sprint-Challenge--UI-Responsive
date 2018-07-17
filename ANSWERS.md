<!-- Answers to the Self Study Questions go here -->

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?

2. Describe the difference between `display: block;` and `display: inline;`.

3. While using flexbox, what axis are you using when you use the property: `align-items: center`?

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?

###Answers

1. They all have the same specifity because they are classes but `box 3` is the last class referenced so it would take precedence over the other classes

2. The difference between `display: block` and `display: inline` are that Elements with `display:inline-block`are like `display:inline elements`, but they can have a width and a height. That means that you can use an inline-block element as a block while flowing it within text or other elements.

3. You are using the `cross axis`.

4. `fixed layout` aka "static" is old and updated and it has a fixed width in pixels. The ‘container’ of the website is programmed to not move (that’s where the name ‘static’ comes from). This width stays the same independently of which screen size or resolution the viewer has. It appears that the width of 960px is the most widely used size for fixed-layout websites. The drawback is that when viewing such layout on smaller screens you get the hideous horizontal scroll, which ruins the overview, experience an usability. The pros of having full control over how the interface looks… does not really outweigh the cons.

    `adaptive layout` means that there are several versions of the layout which are displayed based on the screen size of the viewer. Think of it as several fixed layout designs, layout A is displayed when the screen size is within size range. The benefit is obviously that the designer has more certainty that the user will have an optimal experience. Another plus point is that the website with such layout should load pretty fast, because there is not much adjustments of the size and position of elements going on when loading it — the server sends exactly what has to be loaded. The drawback is that every layout should be designed with care, and that takes time and effort.

    `fluid layout` With fluid layout you specify sizes not in pixels, but in percentages. Meaning, if the screen size changes, the proportion of elements will stay the same. The drawback is that on smaller screens the columns can get really narrow. Now imagine how a block of text in a narrow and very tall cell looks like. Or, adding some elements like images and video which should stay of a fixed size. This combination is asking for trouble.  The pros is that this is a more flexible layout than fixed. But that only seems like a good option when compared to the only option that is worse. It is still borderline impossible to design an interface with fluid layout that would look good on both large and small screens — it can get too busy on small screens and way too empty on big ones.

    `responsive layout` Responsive design takes the best of the two worlds of fluid and adaptive design. There are several so-called breakpoints, which divide all possible screen sizes in ranges. The interface has slightly (or completely different) layout depending on the screen size it’s viewed on. Also, depending on the screen size, elements will stretch or shrink accordingly. Responsive layout provides a custom experience for whichever screen size it’s viewed on.  Responsive layouts are pretty much an expectation nowadays. The drawback is needing even more design and testing effort than for adaptive layouts.

    Adaptive layout can quite withstand the variety of screen sizes, however responsive layout still wins, as it helps avoid the potentially too busy or too empty screen space.

    5. `Max-width` will help the designer to exert control on the page and limit the change to only the height on the device.





     

