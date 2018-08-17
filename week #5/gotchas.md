## Gotchas

We can find the shortest route in _O(N + M)_ time, where _N_ is the number of users and _M_ is the number of connections between them.

It's easy to write code that can get caught in an infinite loop for some inputs! Does your code always finish running?

What happens if there's no way for messages to get to the recipient?

What happens if the sender tries to send a message to themselves?
