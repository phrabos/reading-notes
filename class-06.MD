# Understanding the problem domain is the hardest part of programming
- This article was a problem domain for me. I think the point is to say that it is hard to start writing code that solves a problem if you don't understand the problem you are trying to solve. The example used was trying to put together a jigsaw puzzle without the picture of the finished puzzle. Understanding the problem is the most critical piece of the equation.
# From the Duckett JS book

## Chapter 3: “Object Literals” (pp.100-105)
- Objects group together a set of variables and functions to create a model of something in the real world
    - variables become properties when inside of an object
    - functions become methods when inside of an object
        - properties and methods have a name and value which is called a key and a value
            - key value syntax is key : value
- object literal syntax:

```
const hotel = {
name: 'Quay',
rooms: 40,
booked: 25
checkAvailability: function(){
    cool zone
    }
};
```  
- to access properties and methods in a function:
    - ``hotel.name``
    - ``hotel.checkAvailability()``
## Chapter 5: “Document Object Model” (pp.183-242)
- The browser represents the webpage using a DOM tree
- DOM is implemented by browser makers and has two primary purposes:
    1) Making a model of HTML page
    2) accessing and changing the HTML page
- DOM trees have 4 nodes
    1) document node
        - represents the entire page and the starting point for the DOM tree
    2) element nodes
        - can be selected by their:
            - ID
            - class
            - tag name
            - or CSS selector syntax
    3) attribute nodes
    4) text nodes
- Working with DOM tree
    1) Access the Elements
        - getElementByID("")
        - querySelector("")
        - getElementByClassName()
        - querySelectoreAll()
        - parentNode()
        - firstChild()/lastChild()
    2) Work With the Elements
        - nodeValue - change text of a text node
        - textContent - change text of HTML element
        - change class/ID
- DOM queries can return a single item of a list of items.
    - If a list of items is returned, the list items can be accessed by referencing its index value starting at 0
- Live vs Static nodeList
    - getElementBy... - creates a live list that updates as the page updates
    - querySelector... - creates a static list that does not update
- Node lists can be saved as an array then looped through to change values, properties, etc
- Don't use innerText to change text content, instead use textContent
- use innerHTML to change html content
- use the Chrome Dev Tools to see the structure of the DOM tree