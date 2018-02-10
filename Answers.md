Answer 1: The selector which will be written the last in our css file will have the most specificity weight.
          For example: box2 will have the msot specificity weight in this example:
                       .box{...}
                       .box1{...}
                       .box3{...}
                       .box2{...}
           Specificity rules: Inline --> ID --> Class --> attributes
             
Answer 2: "display:block" will use the total width assigned to the selector
          "display:inline" is the default property of display which does not allow the user to assign width
           or any other properties to the selector.      
           
Answer 3:  Using "align-items: center" the cross axis is being used, whereas for "align-items:center:
           the main axis is used.
           
Answer 4:  Fixed layout: The layout and the widths are fixed in this option. The layout and the width does 
                         not move in this option. These are layouts are easier to make and are the same for
                         every browser.
           Adaptive layout: These layouts are built according to the various screen resolutions. It relies on 
                            predefined screen sizes to adapt itself to resolutions across devices. To create
                            adaptive layouts one has to create different layouts for different screen sizes.                            
           Fluid layout:  This type of layout allows percentge width of the layout components, making  the 
                          components adjust to the screen resolution of the user. Some elements can be kept 
                          as fixed in this layout. Content type with set width cannot be set according to 
                          different screen resolutions.
           Responsive layout: These are the most suitable and popular in todauy's time. It provides precise viewing
                              experience of a website to the userm adapting to all screen devices without creating
                              different layouts for different screen sizes.
                              
Answer 5: To make the website responsive we need to use the property "max-width" on the outer most container
          in order to allow all the content in the container to adjust its width while changing the screen size.