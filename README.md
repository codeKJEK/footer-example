# footer-example
HTML/CSS footer examples for a friend

## Table Method

**NEW** I am not sure if this works in the version of IE that you use but you can try this.  The Table heading and footer print on every page by default.  We can write out content out using tables or HTML (like I did in the example). The Table footer will print on every page but the last page won’t be at the bottom. But we can specify a size for the table footer (leave space at the bottom of the page) then use the position fixed approach to place the footer we want there.  Its always at the bottom of the page and the content never overlaps it.  Its nothing complicate just HTML and CSS.  I am just not sure that version of IE supports it.  More on this approach here: 

https://medium.com/@Idan_Co/the-ultimate-print-html-template-with-header-footer-568f415f6d2a


## Absolute 

The best solution for footers.  Uses the height of the relative parent (.page) which is currently set to 1017px (what we used to use). Then places the footer at the bottom left of the parent container.  You can edit each footer individually or remove it altogether. 

**WARNING:** If the page content is too big for the page it will overlap the footer and in some cases even the next page.
## Fixed
Useful when every footer on every page is the same.  Footer is given a position of fixed which places it at the bottom of every page.  There is only one footer at the bottom that you would have to edit as apposed to every page with Absolute and floating.

**WARNING:** If the page content is too big for the page it will overlap the footer.
## Floating
When you want all the control you can use a floating footer however it is the most time consuming. The footer is left in its DOM order so the content will move it around. Once the page is setup the way you need it, add margin to the top of the footer in order to move it into its desired position. 

**WARNING:** Using this method with dynamic content could push the footer off the page or leave gaps at the bottom.
