1. If you saw this HTML: ```<div class="box box1 box2 box3"></div>``` which class has the most specificity weight?

Ans: they all have equal specificity weight. In css we can modify the specificity. 

eg. 

.box. box1. box2{
// it has a specificity weight of 10+10+10 == 30
}

also in css the last selector will override previous selectors. 
eg. 

.box {
background: red; 
}

.box1 {
background: blue;
}

// in this case the background of the div will be blue;


this also considers the specificity weight; 

.box .box2 {
background: red; 
}

.box1 {
background: blue;
}

// in this case background of the div will be red( more specificity weight); 

--------------------------------------------------------------------------------------

2. Describe the difference between display: block; and display: inline;

Ans: A block level element will start on a new line and will take full width or horizontal space available.
eg . div. 
A inline element will continue with its neighbouring elements and wrap. 
ex. span 
--------------------------------------------------------------------------------------

3.While using flexbox, what axis are you using when you use the property: align-items: center?

ans: cross-axis;
eg. if flex-direction is row(main) then y axis(cross), if flex-direction is column(main) then x axis(cross);

--------------------------------------------------------------------------------------
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?

Fixed: the container dose not change with the screen size, fixed width in px.

Adaptive:  the container dose change its width with respect to breakpoints, there are several versions of the layout which are displayed based on the screen size of the viewer.

fluid: percentage based width , the container size changes according to the screen size maintaining the proportion of the content. 

responsive: combination of both adaptive and fluid. with several breakpoints all possible screen sizes are handeled. 

--------------------------------------------------------------------------------------

5. Why do we need to use the CSS property max-width on the outter most container in a responsive website? 
Ans: we use max-width on the outter most container for: 
		
		- to ensure our desired width and it will not stretch to fit screen sizes larger than our target screen size;
		
		- so that we can calculate width  of all the children of that container according to the max width. (to ensure parent- child relationship for percentage calculation);
		
		
		












