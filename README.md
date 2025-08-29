Q1: What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
--->
By getElementById i can get only one specific element which is given with its specific ID name;
By getElementsByClassName I can get all class name which are specific by their class name;
By querySelector I can get one specific matched element that i want.
By querySelectorAll I can get all that type of matched element i want.

Q2: How do you create and insert a new element into the DOM?
--->
I can create a new element by document.createElement(), and insert it into the DOM by using appendChild().

Q3: What is Event Bubbling and how does it work?
--->
Event bubbling first triggered its target element and then propagates upwards to its parent elements of the document.
if i click to button, it will trigger as button as his target and then propagates upwards to button div, and then parent element of that div, and again parent element of that div. it works like this.

Q4: What is Event Delegation in JavaScript? Why is it useful?
--->
it attach a listener to parent element to control child element. it is useful because, we can control many child element just by add listener to parent element.

Q5: What is the difference between preventDefault() and stopPropagation() methods?
--->
preventDefault() stops the browser default action for an event,
stopPropagation() stops the event bubbling or capturing of the DOM tree.
