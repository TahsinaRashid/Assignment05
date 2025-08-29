### 6. Answer the following questions clearly:

**1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

Answer: **getElementById** uses only one id attributes to select an element.
Whereas **geElementByClassName** that has a class to select every element.
Then **querySelector** uses when we need to select a specific element but we do not have any id then we use this but it only selects the first matched element.
Finally **querySelectorAll** means when we need to select all the element according to the selectors then we use it.






**2. How do you create and insert a new element into the DOM**?

Answer:
To create and insert a new element into the Document Object Model (DOM), there are three steps to follow

1.Create the element: Use document.createElement().

2.Modify the element: Set its content, add classes or set attributes.

3.Insert the element: Add it to an existing parent element on the page using a method like appendChild() or insertBefore().



**3. What is Event Bubbling and how does it work?**

Answer:Event bubbling is the natural way events work on a webpage. When we interact with an element (like clicking a button) that event doesn't just stay on that one element. It's like a chain reaction.
The browser follows this process when an event occurs:

1.Target Phase: The event reaches the element that was clicked (the event.target).

2.Bubbling Phase: The event then moves from the target element up through each of its ancestors to the document object.


**4. What is Event Delegation in JavaScript? Why is it useful?**

Answer:
Event delegation is a technique where we add a single event listener to a parent element instead of adding a separate listener to each of its child elements.
Event delegation is a powerful and efficient technique for two main reasons:
1. Improved Performance
2. Handles Dynamic Content


**5. What is the difference between preventDefault() and stopPropagation() methods?**

Answer:
preventDefault() prevents a form from submitting, a link from navigating or a checkbox from being checked. It stops an action.

stopPropagation() prevents an event from "bubbling up" and triggering event listeners on parent elements.It stops a journey.


