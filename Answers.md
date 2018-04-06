Q: If you saw this HTML: <div class="box box1 box2 box3"></div> which class has the most specificity weight?

A: box3 has the most weight. 





Q: Describe the difference between display: block; and display: inline;.

A: Display: inline uses the least amount of white space possible around your content.  Display: block has height and width and margin, 
white space that you can move your content around in. 


Q: While using flexbox, what axis are you using when you use the property: align-items: center?
A: The cross-axis. 


Q: What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?


A: In Static layout, the dimensions are set, and do not change even if you adjust the size of your window. 

In Adaptive layout, the page uses fixed breakpoints to change the format of the content.  So at 800pixels it will 
change its format to look good on tablet, then change again to fit a mobile screen. 

In Fluid layout, the page uses percentages to fill the dimensions of the page.  So if you stretch, it will stretch, 
if you shrink, it will shrink, but the layout of the content stays the same. 

Responsive is like Fluid + Adaptive. The page will shrink or stretch based on the dimensions of the window, but it will 
also rearrange it's content when it gets to certain fixed breakpoints.  This way it can account for variances in width, but also avoid 
looking squished together or stretched out. 




Q: Why do we need to use the CSS property max-width on the outter most container in a responsive website?
A: So that the content doesn't get stretched and become unreadable or unpleasant to look at past a certain width. 
