1. If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

        In HTML, specificity weight increases going L to R. So in this case box 3 has the most specificity weight. 

2. Describe the difference between display: block; and display: inline;.
        
        When elements are set to display block they try to take up all the space infront of them no matter the size of their content, whereas in display inline the elements will try to be only as big as their conent. 

3. While using flexbox, what axis are you using when you use the property: align-items: center?

        y-axis if flex-direction is set to row (default).

4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

        fixed: this webpage will have horizontal scrollbar since it will make zero adjustments to accomodate the user's viewport.
        
        adaptive: uses media queries to adapt to varying viewports; however, horizontal scrollbar may still be present if width and font sizes are not in %s and rems respectively.
        
        fluid:  100% fluid webpage will not have any constraints (no max-width) so the page layout will span the entire viewport. 
        
        responsive: implements media queries, fluidity aspects (max/min-width), and % based layout to yield a webpage that adjusts with varying viewport sizes. 

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website?
        In order to provide a constraint (limit the width) so that the page is not 100% fluid or spans the entire width of the vieport. 