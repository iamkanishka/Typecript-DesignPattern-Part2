### Iterator Design Pattern
The Iterator will commonly contain two methods that perform the following concepts.

next: returns the next object in the aggregate (collection, object).
hasNext: returns a Boolean indicating if the Iterable is at the end of the iteration or not.
The benefits of using the Iterator pattern are that the client can traverse a collection of aggregates(objects) without needing to understand their internal representations and/or data structures.