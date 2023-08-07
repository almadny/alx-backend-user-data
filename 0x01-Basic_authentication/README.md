Basic Authentication Tasks
Basic Authentication is a simple way to secure API endpoints from a server side.
It simple has to do with users supplying their username and password before accessing resources on the server.
This username and password is joined like username:password and then encoded using base64 encoding.
The encoded string is then passed in the request header using the authorization parameter.
The header is decoded at the server side to allow access to the API resources.
