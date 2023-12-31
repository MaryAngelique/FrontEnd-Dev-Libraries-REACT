You can design a more complex stateful component by combining the concepts covered so far. These include initializing state, writing methods that set state, and assigning click handlers to trigger these methods.

The Counter component keeps track of a count value in state. There are two buttons which call methods increment() and decrement(). Write these methods so the counter value is incremented or decremented by 1 when the appropriate button is clicked. Also, create a reset() method so when the reset button is clicked, the count is set to 0.

Note: Make sure you don't modify the classNames of the buttons. Also, remember to add the necessary bindings for the newly-created methods in the constructor.

Tests
Counter should return a div element which contains three buttons with text content in this order Increment!, Decrement!, Reset.
The state of Counter should initialize with a count property set to 0.
Clicking the increment button should increment the count by 1.
Clicking the decrement button should decrement the count by 1.
Clicking the reset button should reset the count to 0.