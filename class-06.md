#  Objects, and the DOM

## Objects:

* Objects group together a set of variables and functions to create a model
  of a something you would recognize from the real world. In an object,
  variables and functions take on new names.

## Document Object Models(DOM)

* The Document Object Model (DOM) specifies how browsers should create a model of an HTML
  page and how JavaScript can access and update the contents of a web page while it is in the
  browser window.


 * Each node is an object with methods and properties. Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser.

![image](/image/node.png)


### ACCESSING ELEMENTS

* DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

* Sometimes you will just want to access one
individual element (or a fragment of the page that
is stored within that one element). Other times you
may want to select a group of elements.


##### METHODS THAT RETURN A SINGLE ELEMENT NODE:

* getElementByld( ' id ')
Selects an individual element given the value of its i d attribute . The HTML must have an id attribute in order for it to be selectable.

* querySel ector( ' css selector')
Uses CSS selector syntax that would select one or more elements .
This method returns only the first of the matching elements.

* getEl ementsByClassName( 'class ' )
Selects one or more elements given the value of their cl ass attribute. The HTML must have a cl ass attribute for it to be selectable. This method is faster than querySe 1ectorA11 () . 

* getEl ementsByTagName( ' tagName ')
Selects all elements on the page with the specified tag name. This method is faster than querySe 1ectorA11 ().

* querySelectorAll ( ' css selector')
Uses CSS selector syntax to select one or more elements and returns all of those that match.






