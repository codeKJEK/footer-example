# footer-example
HTML/CSS footer examples for a friend

##Absolute 
The best solution for footers.  Uses the height of the relative parent (.page) which is currently set to 1017px (what we used to use). Then places the footer at the bottom left of the parent container.  You can edit each footer individually or remove it altogether. 
###WARNING: 
If the page content is too big for the page it will overlap the footer and in some cases even the next page.
##Fixed
Useful when every footer on every page is the same.  Footer is given a position of fixed which places it at the bottom of every page.  There is only one footer at the bottom that you would have to edit as apposed to every page with Absolute and floating.
###WARNING: 
If the page content is too big for the page it will overlap the footer.
##Floating
When you want all the control you can use a floating footer however it is the most time consuming. The footer is left in its DOM order so the content will move it around. Once the page is setup the way you need it, add margin to the top of the footer in order to move it into its desired position. 
###WARNING: 
Using this method with dynamic content could push the footer off the page or leave gaps at the bottom.
