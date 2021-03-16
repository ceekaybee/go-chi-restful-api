# go-chi-restful-api

# Go and `chi` RESTful API

This project demonstrates a simple RESTful API built with Go and [`chi`](https://github.com/go-chi/chi). This API provides the following endpoints:

* `GET /` - Verify whether or not the service is up and running ("health check"). Returns the "Hello World!" message
* `GET /posts` - Retrieve a list of posts.
* `POST /posts` - Creates a post.
* `GET /posts/{id}` - Retrieve a single post identified by its `id`.
* `PUT /posts/{id}` - Update a single post identified by its `id`.
* `DELETE /posts/{id}` - Delete a single post identified by its `id`.

## Get Started

Run the server

```shell
$ go run .
```
