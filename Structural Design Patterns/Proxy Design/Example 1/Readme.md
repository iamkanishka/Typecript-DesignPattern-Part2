### Proxy Design Pattern

The Proxy design pattern is a class functioning as an interface to another class or object.

A Proxy could be for anything, such as a network connection, an object in memory, a file, or anything else you need to provide an abstraction between.

Types of proxies,

Virtual Proxy: An object that can cache parts of the real object, and then complete loading the full object when necessary.

Remote Proxy: Can relay messages to a real object that exists in a different address space.

Protection Proxy: Apply an authentication layer in front of the real object.

Smart Reference: An object whose internal attributes can be overridden or replaced.

Additional functionality can be provided at the proxy abstraction if required. E.g., caching, authorization, validation, lazy initialization, logging.

The proxy should implement the subject interface as much as possible so that the proxy and subject appear identical to the client.

The Proxy Pattern can also be called Monkey Patching or Object Augmentation