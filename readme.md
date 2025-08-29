1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
getElementById("id") → returns a single element by its unique id.
getElementsByClassName("class") → returns a live collection of elements with the given class.
querySelector("selector") → returns the first element that matches a CSS selector.
querySelectorAll("selector") → returns all matching elements as a static NodeList.

2. How do you **create and insert a new element into the DOM**?
Creation -> By using "document.create('element-tag')"
Insertion -> By using "parent.appendChild(element)

3. What is **Event Bubbling** and how does it work?
Event bubbling means when an event happens on an element, it first runs the handler on that element, then on its parent, and keeps going up the DOM tree.

4. What is **Event Delegation** in JavaScript? Why is it useful?
Event delegation is when i add an event listener to a parent element instead of individual child elements. The event bubbles up from the child, and the parent handles it. It’s useful because it saves memory, avoids adding too many listeners, and works for dynamically added elements.

5. What is the difference between **preventDefault() and stopPropagation()** methods?
preventDefault() → stops the default action of an element (e.g., a link opening a page).
stopPropagation() → stops the event from bubbling up to parent elements.