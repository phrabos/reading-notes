Javascript is a synchronous language by default, which means code cannot run in parallel. Lines of code are executed in a series one after the other. A callback is a function that is passed as a value to another function. Callback functions can get complicated when there are multiple levels of nesting. Async/Await is a feature added to JavaScript to prevent the need for nested callbacks. Async/Await is syntactic sugar applied on top of promises. Using Async infront of an expression declaration will return a promise that can be later used by passing the .then method  to the function. Most modern web APIs use promises. A promise represents an operation that hasn't completed yet. Promises are similar to event listeners.
Fetch is an API for acdessing and manipulating parts of the http pipeline such as requests and responses. Fetch works with JSON method. fetch() makes newtork request to a url and returns a promise. 