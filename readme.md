# Recipe CRUD API

This is a simple CRUD API for managing recipes using Node.js, Express.js, and MongoDB.

## Installation
1. Clone the repository
2. Run `npm install`
3. Start the server with `node server.js`

## API Endpoints

- `POST /api/recipes/` - Create a new recipe
- `GET /api/recipes/` - Get all recipes
- `GET /api/recipes/:id` - Get a recipe by ID
- `PUT /api/recipes/:id` - Update a recipe by ID
- `DELETE /api/recipes/:id` - Delete a recipe by ID

## Sample Request (Postman)
https://documenter.getpostman.com/view/15579488/2sAYX9mL1i
Refer the above link to see API documentation
## Error Handling
Proper error handling implemented for validation and missing resource cases.