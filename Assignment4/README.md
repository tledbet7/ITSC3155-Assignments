# Assignment 4 - FastAPI Implementation

This assignment focuses on creating a simple API using the FastAPI framework in Python.

## Features

- GET request to return a Hello World message.
- GET request to retrieve an item using an item ID and optional query parameter.
- PUT request to update an item using a request body.
- Pydantic model to validate the item information.

## Running the Application

Install FastAPI and Uvicorn, then run the application using:

`uvicorn main:app --reload`

Open `http://127.0.0.1:8000/docs` to test the API endpoints using the interactive documentation.
