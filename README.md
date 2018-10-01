# node-tests
this app contains the tools and library used for testing your app and server. library like supertest and expect were used

## using expect

expect lets you write better assertions.
When you use expect, you write assertions similarly to how you would say them, e.g. "I expect this value to be equal to 3" or "I expect this array to contain 3". When you write assertions in this way, you don't need to remember the order of actual and expected arguments to functions like assert.equal, which helps you write better tests.

## Spies
expect also includes the ability to create spy functions that can track the calls that are made to other functions and make various assertions based on the arguments and context that were used.

## supertest
We may pass an http.Server, or a Function to request() - if the server is not already listening for connections then it is bound to an ephemeral port for you so there is no need to keep track of ports.

SuperTest works with any test framework 
