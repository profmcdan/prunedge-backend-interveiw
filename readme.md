# Software Developer Application Test (Backend)

Create a REST API for a restuarant service a, “**Mock Eateries**”

## User Types

There should be:

- **Admin accounts** which are used to
  - signup/login
  - manage recipe category (add, remove, edit, view)
  - create recipe under each category (add, remove, edit, view)
  - Generate unique links for recipe
- **Users accounts** who can
  - signup/login
  - view categories
  - view recipes
  - add recipe to cart
  - robustly search category/recipe
- Only the search endpoint should be availble to the public.

## Authentication and Session Management

1. Use redis as your session store.
2. Authentication and Authorization for admin and user accounts should be done using `passport` and `JWT`.

## Tools/Stack

- NodeJs (JavaScript or TypeScript)
- MongoDB/POSTGRES/MYSQL
- Redis
- Docker
- POSTMAN
- Jest
- Express

## Tests

Unit tests are a must, submissions without tests will be ignored.

## Submission

1. Your API endpoints should be documented in POSTMAN.
2. Seed the db with lots of data before final submission.
3. Code should be hosted on a git repository, Github preferably.
4. The API should be hosted on a live server (e.g. https://heroku.com)

## Bonus

You'll get bonus points for:

1. `containerization` using `docker`.
2. Thorough documentation using POSTMAN.
3. e2e tests and use of `Jest` for tests.
4. `web caching` API endpoints using `Redis`.
5. Implementing `rate limiting` for user account API access.

## Time Duration

7 days

## NB:

Please send an email to acknowledge the receipt of this document.
