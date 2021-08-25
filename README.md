# footer-example

HTML/CSS footer examples for a friend

## Table Method

### How it works

Create a table inside the body tag.  Inside the table you will need a table body and a table footer. The table body only needs one row and one column you put all of the letter content inside of that one row and column.  The table footer only needs one row and one column, the table footer is left blank.  CSS styles the footer-space to the exact same size as the footer.  The table footer leaves the space at the bottom of the page. Below the table you will need a footer div.  The footer div is placed at the bottom of the page via Fixed postion CSS.  
**Note** the footer will be placed at the bottom of the page but there will be a gap based on your browsers print margin preferences.  The content will now move to the next page once it runs into the table footer.  
**Cover footer on first page** you can cover a footer using the cover div placed at the bottom of the page. This div is placed absoultly from the top its height width and placement are based on the .cover CSS  

**NEW** I am not sure if this works in the version of IE that you use but you can try this.  The Table heading and footer print on every page by default.  We can write out content out using tables or HTML (like I did in the example). The Table footer will print on every page but the last page won’t be at the bottom. But we can specify a size for the table footer (leave space at the bottom of the page) then use the position fixed approach to place the footer we want there.  Its always at the bottom of the page and the content never overlaps it.  Its nothing complicate just HTML and CSS.  I am just not sure that version of IE supports it.  More on this approach here: 

https://medium.com/@Idan_Co/the-ultimate-print-html-template-with-header-footer-568f415f6d2a