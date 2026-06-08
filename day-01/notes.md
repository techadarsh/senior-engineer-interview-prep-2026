# Day 01: Javascript Runtime and Node.js Execution Model

Today's goal is to understand how javascript code actually runs.

This topic is important because JavaScript, TypeScript, Node.js, React, GraphQl, resolvers, API calls, async data fetching, frontend rendering, backend latency, and production debugging all depend on this foundation.

--- 

## 1. What is JavaScript?

**Interview answer**
Javascript is  a high-level, single-threaded, dynamically typed programming language. It is mainly used for web development, but with Node.js, it is also widely used for backend development. JavaScript supports asynchronous programming using callbacks, promises, and async/await. It has a rich ecosystem of libraries and frameworks, making it versatile for building various applications.

**In-depth answer**
JavaScript is a programming language mainly used to build dynamic web applications. 

It runs in two major environments: 
    the browser and Node.js. 
    
    In the browser, JavaScript is used to create interactive web pages, while in Node.js, it is used for server-side development.

ex: 
```javascript
button.addEventListener("click", () => {
    console.log("Button clicked!");
})
```

ex: 
```javascript
const http = require("http");

http.createServer((req, res) => {
    res.end("Hello From Node.js!");
}).listen(3000, () => {
    console.log("Server is running on port 3000");
});
```
