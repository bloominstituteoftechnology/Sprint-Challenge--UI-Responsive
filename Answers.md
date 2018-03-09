1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

    The `class="box box1 box2 box3"` has more specificity weight, it is more specific on which element it is being referred to. Now, any thing in that class has the same specificity weight. It just depends which is the last to be called.

2. Describe the difference between display: block; and display: inline;.

    Inline is the default value for elements. Wrapping text around elements like `<span>, <b> or <i>` and having text continue will not break the flow of the text. The Block will break the flow of text. You can think of a block elements that are like a `<div>, <ul>, <h1>, <p>` and more.

3. While using flexbox, what axis are you using when you use the property: align-items: center?

    The cross-axis.

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

    A Fixed layout is static, in other words it stays as a one size using pixels for like width for example. So if you build a website for a desktop screen of lets say 1100 pixels wide then when a mobile user looks at the website from his/her phone then it will look too big for the screen and not look good. Not mobile friendly. Same if you build an app for a mobile screen with a width of 400 pixels, when the user visits the website on their tablet or laptop it will look too small and not good.

    A Adaptive layout will have different fixed screen sizes set in pixels also. It has break points that when reached the layout will adapt. This app will have different screen sizes for the user so if uses a laptop then it looks nice and if he uses his mobile device then there is a different screen to fit the mobile device screen. But if you are on a laptop/desktop and you change the width on your browser then things start to look messy. You will see a horizontal scroll bar, who wants that?!

    A Fluid layout lets you specify sizes not in pixels but in percentages. So when you change the screen size in you laptop/desktop, the elements will start to change but keep its layout. The issue is when you go to small and things start to get messy.

    A Responsive layout will let you use a Adaptive layout and a Fluid layout. As you make the screen smaller on a desktop/laptop the elements will move and adjust until you hit a break point. The break point can change the layout, lets say there is an image that doesn't look good at certain size so what you can do is remove that image when that break point is reached. The screen will continue to adapt as the screen gets smaller or if the user is using a mobile device.


5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

    So we can set certain width percentage to the children of that outter most container (parent container) depending on its max-width of the outter most container.