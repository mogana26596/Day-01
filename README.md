# Day-01

Difference between HTTP1.1 and HTTP2:

HTTP1.1:
It works on the textual format.
There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
It uses requests resource Inlining for use getting multiple pages
It compresses data by itself.

HTTP 2:
It works on the binary protocol.
It allows multiplexing so one TCP connection is required for multiple requests.
It uses PUSH frame by server that collects all multiple pages 
It uses HPACK for data compression.
HTTP2 is much faster and more reliable than HTTP1.

Objects & its internal representation in javascript:

The Object type represents one of JavaScript's data types. It is used to store various keyed collections and more complex entities. Objects can be created using the Object() constructor or the object initializer / literal syntax.
The Object constructor creates an object wrapper for the given value.
If the value is null or undefined, it will create and return an empty object.
If the value is an object already, it will return the value.
Otherwise, it will return an object of a Type that corresponds to the given value.

Constructor:
Object(): Creates a new Object object. It is a wrapper for the given value.

Static methods:
Object.assign()
Object.create()
Object.defineProperty()
Object.defineProperties()
Object.entries()
Object.freeze()
Object.fromEntries()
