## Inside The JavaScript Engine - How Code Gets Executed.

**- Heap**: Heap is a long term memory. It is all about memory allocation. It stores data in our system memory and manages access to it. It meaning "the browser". JavaScript functions are stored in the heap

**- Stack**: This is the short term memory and it manages our program flow (function calls and communication).

JavaScript is single threaded. JavaScript can only do one thing at a time.

There's an important concept that's not part of the JavaScript engine but of modern browsers like Chrome browsers etc. This concept is called the **Event Loop**. It helps us with asynchronous code, things like event listeners, 