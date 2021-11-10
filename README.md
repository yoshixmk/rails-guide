# README

I hands-on like [this](https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one)

## API Endpoints

Our API will expose the following RESTful endpoints.

| Endpoint | Functionality                          |
| -------- | -------------------------------------- |
| POST     | /signup Signup                         |
| POST     | /auth/login Login                      |
| GET      | /auth/logout Logout                    |
| GET      | /todos List all todos                  |
| POST     | /todos Create a new todo               |
| GET      | /todos/:id Get a todo                  |
| PUT      | /todos/:id Update a todo               |
| DELETE   | /todos/:id Delete a todo and its items |
| GET      | /todos/:id/items Get a todo item       |
| PUT      | /todos/:id/items Update a todo item    |
| DELETE   | /todos/:id/items Delete a todo item    |

## Prerequisites

rails 6
