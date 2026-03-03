SOLUTION EXERCISE 5

SPECIFITY -> |ID selectors|Class / Pseudo-class selectors|Element 

1.  ul li -> 0-0-2
    There's 2 element selector, the ul and the li.
    This selector take the child of the ul

2.  ul > li -> 0-0-2
    This selector is very similar but only takes
    the close children of ul element

3.  body > #main.mobile a:hover -> 1-2-2
    This selector take the anchor (when the user pass above with
    cursor) , contents in the ancestor element that have both class mobile and id main, close child of the body

4.  div p > span -> 0-0-3
    This selectors have 3 element selectors that take all the span
    close child of the p element, that are child of the ancestor div element

5.  .user .name -> 0-2-0
    This selector take all the element with the class name
    child of their ancestor class user

6.  [href$='.pdf'] -> 0-1-0
    This attribute selector take all the element in the html
    page with the attribute that end with '.pdf' 
    this is a 0-1-0 specifity because this is an attribute selector

7.  :hover -> 0-1-0
    This selector is very similar of the previous one because
    is a pseudo class selector.
    This pseudo class take all the element when the user pass
    with the cursor on them

8.  div .name -> 0-1-1
    This selector, with an element selector and a class selector
    take all the element with the class name children of their
    ancestor div element

9.  a[href$='.pdf'] -> 0-1-1
    This selector takes all the anchor element that have
    the attribute href that end with .pdf on the value

10. .pictures img:hover -> 0-2-1
    This selector Take all the img element, when the user
    pass above with the cursor, contents in the class named pictues

11. .news.breaking.featured -> 0-3-0
    This selector take only the element that have all the 3
    classes

12. .user #name -> 1-1-0
    This selector take all the id named name contents in the
    class named user

13. #name span -> 1-0-1
    This selector take all the span element contents in the
    id name

14. nav#nav > li:hover -> 1-1-2
    This selector take all the li elements, only when the user
    pass with the cursor above them, close child of the element nav which he must also possess the id named nav

15. li:nth-child(2n+1):hover -> 0-2-1
    This selector take all the odd li element only when the
    user pass the cursor above them