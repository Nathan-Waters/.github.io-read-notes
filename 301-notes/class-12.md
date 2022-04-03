# Notes from Read: 12 CRUD
[Home](README.md)

In your own words, describe what each group of status code represents:

100’s = informational status codes
200’s = success codes
300’s = redirection codes
400’s = client error codes
500’s = server error codes

What is a status code 202?
Request Accepted but will finish in the future due to async nature.

What is a status code 308?
Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore.

What code would you use if an update didn’t return data to a client?
204 No Content

What code would you use if a resource used to exist but no longer does?
410 Gone

What is the ‘Forbidden’ status code?
The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

Videos
Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

Why do we need to pull our MongoDB database string out of our server and put it into our .env?
it contains sensitive information like your mongoDB user and password. this also allows you to use the environmental variables outside of local host.

What is middleware?
Software that provides common services and capabilities to applications outside of what is offered by the OS

What does app.use(express.json()) do?
Lets our server accept JSON as a body.

What does the /:id mean in a route?
This is a parameter that we can access by typing in req.params.

What is the difference between PUT and PATCH?
Patch only updates specific informtaion put updates a whole object.

How do you make a default value in a schema?
use the term default

What does a 500 error status code mean?
a 500 error code means error on the server

What is the difference between a status 200 and a status 201?
the difference between error codes 200 and 201 - 201 means you have successfully created an object, which is more specific than the general 200 code
