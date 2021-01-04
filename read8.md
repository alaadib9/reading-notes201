### CSS Layout
There are a lot of CSS frameworks that provide rich set of layouts and patterns.
Normal flow 
 In normal flow, boxes are displayed one after another based on the Writing Mode of the document. This means that if you have a horizontal writing mode, one in which sentences run left to right or right to left, normal flow will display the boxes of block level elements one after the other vertically down the page.
In normal flow, each block-level element sits on top of the next one
syntax would be:
position: static;

Relative positioning moves an element in relation to where it would have been in normal flow.

Floats
Floats are used to shift a box to the left or right, allowing content to display wrapped around it.

position:absolute When the position property is given a value of absolute,the box is taken out of normal flow and no longer affects the position of other elements on the page
Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed
Pages can be fixed width or liquid (stretchy) layouts.
You can include multiple CSS files in one page.