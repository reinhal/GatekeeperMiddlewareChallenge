# GatekeeperMiddlewareChallenge

This is a challenge in Thinkful's Web Development Bootcamp.

You need to create a piece of middleware that parses request for a header with the name x-username-and-password. The value for that header should looke like this: user=user@somewhere.com&pass=password.

The middleware will need to parse the value for this request header, and then attempt to find a user object for the user with that username and password. If the user is located, its object should be added to the request as req.user. If not, req.user will be undefined.

This app has a single endpoint, /api/users/me, which is meant to return the first name, last name, user name, id, and position (aka job title) of an authenticated user. 
