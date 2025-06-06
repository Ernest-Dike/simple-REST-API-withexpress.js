# simple-REST-API-withexpress.js
# Simple REST API with Express.js

## Setup Instructions

1. Clone the repo
2. Run `npm install`
3. Start the server using `node index.js`
4. Server runs on `http://localhost:3000`

## API Routes

### GET `/`
- Returns: "Hello, World!"

### GET `/items`
- Returns all items

### GET `/items/:id`
- Returns a specific item by ID

### POST `/items`
- Creates a new item
- Body: `{ "name": "Item", "description": "Details" }`

### PUT `/items/:id`
- Updates an item by ID
- Body: `{ "name": "New", "description": "Updated" }`

### DELETE `/items/:id`
- Deletes an item by ID

## Example Requests (Postman)

- GET `http://localhost:3000/items`
- POST `http://localhost:3000/items`  
  Body:
  ```json
  {
    "name": "New Item",
    "description": "New Description"
  }
