# Movie Management API

Welcome to the Movie Management API! This project demonstrates a simple API for managing movie information. It allows you to perform operations like retrieving movie details, adding new movies, updating existing ones, and even deleting them.

## Technologies Used

- **Programming Language:** Go (Golang)
- **Web Framework:** Gorilla Mux
- **Data Serialization:** JSON
- **Random Number Generation:** math/rand Package
- **HTTP Server:** net/http Package

## Features

- Retrieve a list of all movies
- Get details about a specific movie
- Add a new movie to the collection
- Update existing movie information
- Delete a movie from the collection

## Getting Started

1. Install Go on your machine if not already installed.
2. Clone this repository: `git clone https://github.com/your-username/go-movies-crud.git`
3. Navigate to the project directory: `cd go-movies-crud`
4. Run the server: `go run main.go`
5. Access the API at: `http://localhost:8000`

## Usage

- To get a list of all movies: `GET /movies`
- To get details of a specific movie: `GET /movies/{id}`
- To add a new movie: `POST /movies`
- To update a movie's details: `PUT /movies/{id}`
- To delete a movie: `DELETE /movies/{id}`

## Example Request (cURL)

- Add a new movie:
```bash
curl -X POST -H "Content-Type: application/json" -d '{"isbn": "123456", "title": "New Movie", "director": {"firstname": "Jane", "lastname": "Doe"}}' http://localhost:8000/movies

## Credits
- I built this project following Akhil Sharma tutorial- https://github.com/AkhilSharma90 .
