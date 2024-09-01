# JavaScript and Node.js

Node.js allows you to run JavaScript on the server side. It uses an event-driven, non-blocking I/O model, making it efficient and scalable.

## Key Concepts
- **Modules**: Reusable code blocks (`require('module')`).
- **npm**: Node.js package manager for managing dependencies.
- **Event Loop**: Handles asynchronous operations.
- **Express.js**: Popular framework for building web applications with Node.js.

## Example
```javascript
// Simple HTTP server using Node.js
const http = require('http');

const server = http.createServer((req, res) => {
    res.statusCode = 200;
    res.setHeader('Content-Type', 'text/plain');
    res.end('Hello, World!\n');
});

server.listen(3000, '127.0.0.1', () => {
    console.log('Server running at http://127.0.0.1:3000/');
});
```

## Learning Resources

- [Node.js Official Documentation](https://nodejs.org/docs/latest/api/)
- [MDN Web Docs: Node.js](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs)

## Next Steps

1. Experiment with building small Node.js applications.
2. Explore npm packages and use them in your projects.
