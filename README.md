# Altair JSON Placeholder

Altair JSON Placeholder is a free online REST API that provides fake data for testing and prototyping. It is designed for frontend, backend, and mobile app development.

Final Website Link: [Here](https://json-placeholder-olive.vercel.app/)

## Features

- Fake API endpoints for **Users, Posts, and Todos**.
- Supports all **HTTP methods**: `GET`, `POST`, `PUT`, `PATCH`, and `DELETE`.
- Simulated error responses for testing (`404 Not Found`, `429 Too Many Requests`, `500 Internal Server Error`).
- Has sample routes for **login, register and logout**. They are not actual authentication functionalities, but simple API for practice.
- Simple and fast API for quick integration into projects.

## Available Endpoints

- **Users:** `/users` (all users), `/users/{id}` (specific user)
- **Posts:** `/posts` (all posts), `/posts/{id}` (specific post)
- **Todos:** `/todos` (all todos), `/todos/{id}` (specific todo)
- **Error Simulations:**
  - `/404` - Simulates a 404 Not Found error.
  - `/429` - Simulates a 429 Too Many Requests error.
  - `/500` - Simulates a 500 Internal Server Error.

## Authentication Endpoints

- **Login:** `/login/` (Requires `email` and `password` in request body)
- **Register:** `/register/` (Requires `username`, `email`, `password`, `confirmPassword`)
- **Logout:** `/logout/`

## Usage

To use the API, send requests to the appropriate endpoints using any HTTP client like **Postman**, **cURL**, or **Axios**.

Example `GET` request:

```sh
curl -X GET https://your-api.com/posts
```

You can also test APIs using **Postman and Thunder Client** if you do not own _Linux_

## Deployment

This API is deployed using **Express.js** and is configured for deployment on **Vercel**.

## License

This project is open-source and free to use.

---

🚀 **Altair JSON Placeholder – Making API Testing Simple!**
