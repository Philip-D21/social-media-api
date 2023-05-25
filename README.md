## Auth Routes
GET / unprotected routes  => home route to display all posts content
GET /login (unprotected) ==> authenticate a new user
GET /logout (unprotected) ==> logout a user


##  POST  API Routes
GET  /api/v1/posts (protected) => Return all posts
POST  /api/v1/posts (protected) => Add all posts to the DB
PUT  /api/v1/posts/:id (protected) => Update a posts
DELETE /api/v1/posts/:id (protected) => Delete a post by ID
GET /api/v1/posts/:id (protected) => gets a post by unique id