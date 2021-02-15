# CSS LAYOUT

### What's The Layout?

* The layout it is a collection of popular layouts and patterns made with CSS.

### positioning schemes

* CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position
property in CSS.

###### normal flow 
 * position:static: In normal flow, each block-level element sits on top of the next
one. Since this is the default way in which browsers treat HTML elements, you do not
need a CSS property to indicate that elements should appear in normal flow, but the syntax
would be: position: static; I have not specified a width property for the heading element, so you can see how it stretches the width of the entire browser window by default.

###### relative postitioning 
* position:relative: moves an element in relation to where it would have been in normal flow.
You can indicate that an element should be relatively positioned using the position property with a value of relative.

###### absolute possitioning 
* position:absolute: When the position property is given a value of absolute,
the box is taken out of normalflow and no longer affects the position of other elements on the page. (They act like it is notthere.)

###### Fixed Positioning
* position:fixed: Fixed positioning is a type of absolute positioning that requires the position property
to have a value of fixed.

  
#### z-index
* When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the
elements that appear later in the HTML code sit on top of those that are earlier in the page.
If you want to control which element sits on top, you can use the z-index property. Its value
is a number, and the higher the number the closer that element is to the front. For example, an
element with a z-index of 10 will appear over the top of one with a z-index of 5.

#### FLOAT
* The float property allows you to take an element in normal flow and place it as far to the
left or right of the containing element as possible. Anything else that sits inside the containing element will flow around the element that is floated.

* The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)