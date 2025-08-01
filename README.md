# Book Search API

This repository contains a FastAPI-based REST API for searching and managing books. The API allows users to search for books by title, author, or ISBN, and provides endpoints for retrieving book details.

## Features

- Search books by title, author, or ISBN
- Retrieve detailed information about a specific book
- List all available books
- Add, update, or delete books (optional, depending on implementation)

## Tech Stack

- Python 3.10+
- FastAPI
- Uvicorn (for local development server)

## Getting Started

### Prerequisites

- Python 3.10 or higher
- pip

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/book-search-api.git
   cd book-search-api
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

### Running the API

Start the development server with:

```sh
uvicorn main:app --reload
```

The API will be available at [http://localhost:8000](http://localhost:8000).

### API Documentation

Interactive API docs are available at [http://localhost:8000/docs](http://localhost:8000/docs).

## Project Structure

```
.
├── app/
│   ├── main.py
│   ├── models.py
│   ├── schemas.py
│   └── ...
├── requirements.txt
└── README.md
```

## License

This project is licensed under the MIT License.