# Review Questions

## What is Node.js?
Node.js is a JS framework and an open source environment for servers

## What is Express?

Express is a minimalist framework for node.js making it easier to create endpoints and handling requests

## Mention two parts of Express that you learned about this week.

express Router
middleware 

## What is Middleware?

middleware is a function that has access to the req and res objects and is able to call the next middleware

## What is a Resource?

Anything that we'd send back in our API should qualify as a ressource

## What can the API return to help clients know if a request was successful?

http status codes

## How can we partition our application into sub-applications?

Using express Router and then seperating everything into different Routes

## What is CORS and why do we need it?

middleware that allows "cross origin requests" (allows other servers  / URLs , to navigate to our URLs or apis)
