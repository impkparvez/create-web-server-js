# Introduction

### Network Programming

The first step is to make programs talk over a network. This is also called `socket programming`

### Protocols & Communication
In order to communicate over a network, the data sent over the network must conform to a specific format called a `protocol`. Learn how to create or implement any network protocols by using HTTP as the target.


## Project-Centric
An outline of each step:

1. TCP echo server.
    - Socket primitives in Node.JS
    - Event-based programming.
    - async/await and promises.
2. A simple messaging protocol
    - Implementing a network protocol in TCP.
    - Working with byte streams and managing buffers.
3. Basic HTTP server.
    - HTTP semantics and syntax.
    - Generating dynamic content
        - Async generators
4. Core applications
    - Serving static files
        - File IO in Node.JS
        - Programming tip: avoiding resouce leaks.
        - Range requests.
    - Caching control
    - Compression
        - The stream and pipe abstraction.
5. WebSocket.
    - Message-based designs
    - Concurrent programming.
        - Blocking queues.

## Discussions at the End of Chapter
- The gap between toys and the real thing, such as optimizations and applications.
- Important concepts beyond coding, such as event loops and backpressure.
- Design choices.
- Alternative routes.

## Node.js and TypeScript
- The project uses Node.js without any dependencies
- Code samples use TypeScript with type annotations for readability, but the differences from JS are minor
- Mostly data structures + functions, avoiding fancy abstractions to maximize clarity