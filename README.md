 



**Q1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll? **

###Ans getElementById select element using id , Its faster than other method, and it returns only one element.
getElementByClassName finds element using class name, it returns a collection of elements. getElementById, getElementsByClassName returns HTMLelements.
querySelector and querySelectorAll uses Css selector syntax, but querySelector return the first match on the other hand querySelectorAll returns all matching elements. querySelector and querySelectorAll returns nodelist .

**Q2. How do you create and insert a new element into the DOM? **

###Ans Make the element using createElement,then add the content and insert into DOM.

**Q3. What is Event Bubbling? And how does it work? **

 ###Ans Event bubbling means when an event happens on an element, it first runs on that element and then moves upward through its parent elements.

**Q4. What is Event Delegation in JavaScript? Why is it useful? **

 ###Ans Event delegation means putting one event listener on a parent element instead of many listeners on each child. The parent listens for events and checks which child triggered it. Its useful because it saves memory, less repeated code, faster performance.

**Q5. What is the difference between preventDefault() and stopPropagation() methods? **

 ###Ans preventDefault stop browser behavior on the other hand stopPropagation stop event movement.

 

