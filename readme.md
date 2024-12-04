1. What is NodeJS?
Node.js is a runtime environment that allows you to run JavaScript on the server side. Built on Chrome's V8 JavaScript engine, it enables building scalable, fast, and efficient network applications using non-blocking, event-driven I/O.

2. What is V8 Engine?
The V8 Engine is an open-source JavaScript engine developed by Google. It is written in C++ and powers both the Chrome browser and Node.js. It converts JavaScript code into highly optimized machine code using just-in-time (JIT) compilation.

3. What is the Event Loop in NodeJS?
The Event Loop is a core component of Node.js that handles asynchronous operations. It enables non-blocking I/O by managing operations such as reading files, making API calls, or querying databases in a single-threaded environment.

4. What is the use of tsconfig.json file?
The tsconfig.json file in a TypeScript project specifies the root files and compiler options required to compile the project.

5. What are the methods provided by the fs module to manipulate files?
The fs (File System) module in Node.js allows file operations. Common methods include:

File Reading:

fs.readFile(): Reads a file asynchronously.
fs.readFileSync(): Reads a file synchronously.
File Writing:

fs.writeFile(): Writes data to a file asynchronously.
fs.writeFileSync(): Writes data to a file synchronously.
File Deletion:

fs.unlink(): Deletes a file asynchronously.
fs.unlinkSync(): Deletes a file synchronously.
File Renaming:

fs.rename(): Renames a file asynchronously.
fs.renameSync(): Renames a file synchronously.
File Stats:

fs.stat(): Gets file information asynchronously.
fs.statSync(): Gets file information synchronously.

6. What is API?
An API (Application Programming Interface) is a set of rules and protocols for building and interacting with software applications. APIs define how software components should communicate and allow developers to interact with an application's functionality or data.

A REST API provides endpoints like GET /users or POST /login for interacting with a backend system.


1. What is NodeJS?
Node.js is a runtime environment that allows you to run JavaScript on the server side. Built on Chrome's V8 JavaScript engine, it enables building scalable, fast, and efficient network applications using non-blocking, event-driven I/O.

Key Features:

Single-threaded and asynchronous.
Uses non-blocking I/O for high performance.
Ideal for building REST APIs, real-time applications, and microservices.
2. What is V8 Engine?
The V8 Engine is an open-source JavaScript engine developed by Google. It is written in C++ and powers both the Chrome browser and Node.js. It converts JavaScript code into highly optimized machine code using just-in-time (JIT) compilation.

Key Features:

Fast execution of JavaScript.
Memory management and garbage collection.
Used as the core of Node.js to execute JavaScript on servers.
3. What is the Event Loop in NodeJS?
The Event Loop is a core component of Node.js that handles asynchronous operations. It enables non-blocking I/O by managing operations such as reading files, making API calls, or querying databases in a single-threaded environment.

Working:

Incoming requests or operations are pushed onto the Event Queue.
The Event Loop continuously checks the Event Queue for tasks and executes them if the call stack is empty.
Long-running operations (like I/O) are delegated to the Worker Threads or libuv thread pool, and their callbacks are queued for execution.
4. What is the use of tsconfig.json file?
The tsconfig.json file in a TypeScript project specifies the root files and compiler options required to compile the project.

Common Options:

"compilerOptions": Configuration options like target ECMAScript version, module type, strictness settings, etc.
"include": Specifies files or directories to be included.
"exclude": Specifies files or directories to be excluded.
Example:

json
Copy code
{
  "compilerOptions": {
    "target": "ES6",
    "module": "commonjs",
    "strict": true
  },
  "include": ["src/**/*"],
  "exclude": ["node_modules"]
}
5. What are the methods provided by the fs module to manipulate files?
The fs (File System) module in Node.js allows file operations. Common methods include:

File Reading:

fs.readFile(): Reads a file asynchronously.
fs.readFileSync(): Reads a file synchronously.
File Writing:

fs.writeFile(): Writes data to a file asynchronously.
fs.writeFileSync(): Writes data to a file synchronously.
File Deletion:

fs.unlink(): Deletes a file asynchronously.
fs.unlinkSync(): Deletes a file synchronously.
File Renaming:

fs.rename(): Renames a file asynchronously.
fs.renameSync(): Renames a file synchronously.
File Stats:

fs.stat(): Gets file information asynchronously.
fs.statSync(): Gets file information synchronously.
6. What is API?
An API (Application Programming Interface) is a set of rules and protocols for building and interacting with software applications. APIs define how software components should communicate and allow developers to interact with an application's functionality or data.

Example:

A REST API provides endpoints like GET /users or POST /login for interacting with a backend system.
7. What is JSON Format?
JSON (JavaScript Object Notation) is a lightweight data-interchange format that is easy to read and write for humans and easy to parse and generate for machines. It represents data as key-value pairs.
{
  "name": "John",
  "age": 30,
  "isAdmin": false
}

8. Why do we use JSON Format for APIs?
Lightweight: Minimal overhead compared to formats like XML.
Human-Readable: Easy to read and understand.
Language Agnostic: Can be used with any programming language.
Built-in Support: Native support in most modern programming languages, including JavaScript.
Ease of Parsing: Libraries like JSON.parse() and JSON.stringify() make handling JSON straightforward.

9. What is a Framework?
A framework is a pre-written set of tools, libraries, and best practices that provide a foundation for building applications. It simplifies development by handling common tasks like routing, data handling, and templating.

