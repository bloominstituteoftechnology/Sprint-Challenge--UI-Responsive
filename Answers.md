1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

    It depends on which class appears last in the css file. 

    Example 1:
    div .box1 {
        color: red
    }

    div .box2 {
        color: blue
    }

    Example 2:

    div .box1 {
        color: blue
    }
    div .box2 {
        color: red
    }

    In Example 1: div text would be blue. In the Example 2, div text would be red.


2. Describe the difference between display: block; and display: inline;.

display: block sets the element to block-level type, which means it will span all horizontal spacing available and begin on a new line.

display: inline does not begin on a new line and only takes up as much width as necessary. 


3. While using flexbox, what axis are you using when you use the property: align-items: center?

You are using the cross-axis. The cross-axis will be the y-axis if flex-direction is set to row or row-reverse. The cross-axis will be the x-axis if flex-direction is set to column.


4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed layout uses fixed widths to determine container sizes and is not responsive to the user's viewport dimensions.

Adaptive layout uses media queries to optimize layout design based on the user's viewport dimensions, but each layout still employs fixed widths.

Fluid layout uses percent based widths to dynamically adjust content layout based on the user's viewport dimensions.

Responsive layout = Fluid + Adapative layout. Responsive layout employs both media queries and percent based widths to dynamically optimize content layout based on the user's viewport. 


5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?

The max-width setting on the outter most container keeps the website from spreading out beyond a set width if the user's viewport exceeds the max-width setting.