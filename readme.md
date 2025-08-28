        
        Answer 1:
        getElementById: returns a single element the one's id match with the given id. However, id must be unique in html. 
        getElementsByClassName: returns a collection of all elements with that class name. 
        querySelector: returns the first element that matches the CSS selector. Any valid CSS selector is allowed. 
        querySelectorAll: returns a NodeList of all matching CSS selector.



        Answer 2:
        Create new element using document.createElement(tagName);. 
        Then use append, prepend, insertBefore, or insertAdjacentElement as required.

        

        Answer 3:
        Event Bubbling is the process where an event start from the interacted element 
        and moves up through its parent elements to document. 
        When click an element the event is first handled by the target element then 
        the same event moves up to its parent, then grandparent, and repeat this up to document.

        

        Answer 4:
        Event Delegation is a technique, where a single event listener is attached to a parent element, 
        and then handle events for its child elements inside that event listener, using event event bubbling. 
        It is useful because instead of using too many event listener for each child, 
        adding one event listener can to the parent can do the same task.

        
        
        Answer 5:
        preventDefault() function prevent browsers default behaviors. 
        stopPropagation() function prevent an event from bubbling and also does not prevent default behavior function.