

## Qustion1: What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
ANS:
- **getElementById("id")** → Selects a single element by its **id**. Always returns only one element.  
- **getElementsByClassName("class")** → Selects all elements with the  class name. 
- **querySelector("selector")** → Returns the **first matching element** using CSS selectors. 
- **querySelectorAll("selector")** → Returns **all matching elements** as a **NodeList**. 

---

## Qustion2: How do you create and insert a new element into the DOM?
ANS:
First create **Child Element** than **append child** to parent **id** name.


##Qustion3: What is Event Bubbling and how does it work?
---
ANS:

**Event Bubbling** is a process in which an event starts from the **target element** and then propagate to its parent.

##Qustion4: What is Event Delegation in JavaScript? Why is it useful?
---
ANS:
**Event Delegation** is a technique where you add an event listener to a parent element instead of multiple child elements.

##Question5: What is the difference between preventDefault() and stopPropagation() methods?
---
ANS:
**preventDefault()** → Prevents the browser's **default** action.
**stopPropagation()** → Stop the event from **propagating** to parent elements.



