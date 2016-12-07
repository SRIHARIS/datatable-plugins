# Jquery Datatable plugins 1.10.9


Custom Fixed Header
  
Addon script to attach fixed Header.Out of box Fixed Header plugin is not compatible with horizontal scroller.

How to use :  

  1. Include the js & associated css in the page.
  2. Add a timeout function with delay 0 and invoke the init function of add-on,after the datatable initialization code.
  3. If the page is via PJAX, then while leaving the page do not forget to trigger flush. !important
   
Note : This feature is not implemented in the plugin structure of a datatable,because dom querying is required and there are no render callbacks for other plugins.So only way to query dom is after datatable loads.


ScrollButtons
 
Plugin to add scroll buttons to datatable.
  
How to use:  
  1. Include the js & associated css in the page.
  2. In the Datatable Initialization, append 'S' to sdom attribute.
  3. customizations available :
      a. scrollSpeed
      b. scrollDistance
      b. disableDraggableScroll
      

Take a look https://snag.gy/YcIuWq.jpg

