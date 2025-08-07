

# Books API

## Description

A simple REST API built with Node.js and Express to manage a list of books stored in memory. The API supports CRUD operations — Create, Read, Update, and Delete books — without using any database. Ideal for learning backend basics and quick prototyping. Easily tested with Postman.

## Features

- Get all books
- Add a new book
- Update an existing book by ID
- Delete a book by ID

## Technologies

- Node.js
- Express.js

## Getting Started

### Prerequisites

- Node.js installed (v12 or later recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```
   git clone 
   ```
2. Navigate into the project directory:
   ```
   cd 
   ```
3. Install dependencies:
   ```
   npm install
   ```

### Running the Server

Start the server with:

```
node server.js
```

The server will run on port 3000 by default.

### API Endpoints

- **GET /books**  
  Returns a list of all books.

- **POST /books**  
  Add a new book.  
  Request body example:
  ```json
  {
    "title": "1984",
    "author": "George Orwell"
  }
  ```

- **PUT /books/:id**  
  Update an existing book by its ID.  
  You can update title and/or author.

- **DELETE /books/:id**  
  Delete a book by its ID.

### Testing

Use Postman or any other API client to test the endpoints.

## Notes

- Data is stored in-memory, so all books will be lost when the server restarts.
- This project is designed for learning and prototyping only.

## License

This project is open source and free to use.
Now,
<img width="1920" height="1080" alt="Screenshot 2025-08-06 222257" src="https://github.com/user-attachments/assets/40f6e91f-95f1-44b4-8473-85ffdeb3e74a" />
Then by POST:
http://localhost:3000/books — Add a book with JSON body:

json
{
  "title": "1984",
  "author": "George Orwell"
}
{
  "title": "To Kill a Mockingbird",
  "author": "Harper Lee"
}
{
  "title": "The Great Gatsby",
  "author": "F. Scott Fitzgerald"
}


<img width="1920" height="1080" alt="Screenshot 2025-08-06 221057" src="https://github.com/user-attachments/assets/76790a08-785e-44fb-b4dd-f2b4e515b583" />

By using GET:
GET http://localhost:3000/books — Retrieves all books

<img width="1920" height="1080" alt="Screenshot 2025-08-06 221129" src="https://github.com/user-attachments/assets/9a93a531-5139-49c2-b3ae-83807b5409bc" />
By using 
PUT http://localhost:3000/books/1 — Update book with id 1 (provide JSON with new title or author).

<img width="1920" height="1080" alt="Screenshot 2025-08-06 221349" src="https://github.com/user-attachments/assets/47e1e629-ae65-411c-b0a6-a22ed5e01488" />
By using:
DELETE http://localhost:3000/books/1 — Delete book with id 1&2.

<img width="1920" height="1080" alt="Screenshot 2025-08-06 221556" src="https://github.com/user-attachments/assets/76d055ac-b158-4d35-a50b-a5c08ced6f4b" />




