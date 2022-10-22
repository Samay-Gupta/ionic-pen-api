# ionic-pen-api

REST API written in express.js with a MongoDB Database for the IonicPen application.

## API Routes:

[GET] `/api/` => Test API route

[POST] `/api/login/` => Send username and password to login user. Returns authentication key.

[POST] `/api/signup/` => Send user details to createa new user. Returns authentication key.

[GET] `/api/homepage/`=> Retrieve all the data needed for the application homepage.

[GET] `/api/search/` => Search for keywords in Users and Books.

[GET] `/api/books/:id/` => Retrieve a specific books information.

[GET] `/api/books/read/:id/` => Read a book based on the last saved position.

[GET] `/api/books/read/:id/next/` => Read the next chapter of a book.

[GET] `/api/library/` => Get all the books in a users library.

[POST] `/api/library/add/` => Add a new book to a users library.

[DELETE] `api/library/remove/:id/` => Remove a book from a users library.
