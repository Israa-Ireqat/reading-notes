# Call stack
![](https://i.ytimg.com/vi/2ZH_1d8TYVg/maxresdefault.jpg)
###  a mechanism for an interpreter to keep track of its place in a script that calls multiple functions, what function is currently being run and what functions are called from within that function.
## Why It's Necessary?
### The JavaScript engine (which is found in a hosting environment like the browser), is a single-threaded interpreter comprising of a heap and a single call stack. The browser provides web APIs like the DOM, AJAX, and Timers.
The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous. In Asynchronous JavaScript, we have a callback function, an event loop, and a task queue. The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).