1
I think it's each box so box1 box2 box3, because you would code them lower down in the css, and they are more specific
where further to the right in the html and further down
but i am honestly not sure because they are not writtin inside of their own divs its all one big div.
but i'll go with my gut and say box3.
2
display: block puts the element on it's own line
and moves others under it,
display:Inline-block allows elements to be displayed
inline next to each other.
3
align-items uses the cross axis, as opposed to the main axis
main axis is left to right only in one direction unless you change the main axis direction 
cross axis is top to bottom but also can be changed according to the main axis
4
a fixed layout is static and does not change based on browsers size or device,
it really gets destorted and messed up if you don't have the display the same as what the 
developer used to make it.
adaptive layout is where we set media breakpoints for tablet and also mobile,
this way when opened in another divice it will adapt to that size relative.
768px and 400px are the standard break points and it gets kinda funky from,
768-400 and then 400 and below gets kinda weird and crushed.
fluid layout is the one i have the least experience with, but i believe it
completly adjust based on % and has no media queires, i think it just fully adjust
but this one i am the lease sure about.
Adaptive is like fluid where it goes off of % but it also has media queires,
so it's a mix of adaptive and fluid, so that when going to 765-400 it looks fine
and 400< keeps looking good.
5
it's a constrant for the page, without it, the page would go crazy and always go to the edges,
making it really hard to view and ugly, also it gives the code in the desktop view something to divide into,
like 55px/880, that means no matter how big that screen is made the code will still look good,
the view is always being centered and the max width is set so it will all be in good proportions.