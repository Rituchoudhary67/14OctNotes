# 14OctNotes
1. Display Flex :- 
Display flex is the property which we use to make the container flexible. Flexible in the sense we can align the child items according to our need using flex property.
For Parent container :- 
    a. flex-direction :- Flex direction is the property which we use to align our item either in row, column, row-reverse, column-reverse.
    b. justify-content and align-items :- For flex-direction row / row-reverse :- Align items will align the items in vertical direction and justify content will align the items in horizontal.
                    For flex-direction column / column-reverse :- Align items will align the items horizontally and justify content will align the items vertically.
    c. flex-wrap :- Flex wrap is use to wrap the content in the flex-direction. We can use either wrap, wrap-reverse and nowrap (default).
    d. flex-flow :- It is the shorthand for flex-direction and flex-wrap.
        General Syntax :- flex-flow: flex-direction flex-wrap ;
    E.g :- flex-flow: column no-wrap;

    e. Align-content :- Align-content will work when we will provide the flex-wrap as wrap and wrap-reverse. It is use to aligning the items in the vertical direction if flex-direction is row / row-reverse and horizontally for column and column-reverse.

For Child :-
    a. order :- Order is use to give the order to the childs. The minimum number of order given will be at the beginning and the maximum number of the order will be at the end.
    b. flex-grow :- It is the property which we use for the children like how speedly they should grow. By default the flex-grow is 0.
    c. flex-shirnk :- It is the property which we use for the chilren so that how speedly they should shrink. The maximum shirnk value will shrink faster than others.
    d. flex-basis :- It is use to give the initial length for the child. Lets say we have flex-direction row so it will change the width of child and if flex direction is column than it will change the height of the child
    e. flex :- It is the shorthand for flex-grow, flex-shirnk and flex-basis.
        General Syntax :-  flex : flex-grow flex-shirnk flex-basis;
        E.g. :- flex: 2 4 200px;
    f. align-self :- It is use to align the child either at start, end, center depending upon the flex-direction.
