# E-commerce Back End Starter Code
# E-commerce Back End

This E-commerce back end application provides the necessary API routes to make your e-commerce website function. It uses an Express.js server and Sequelize to interact with a MySQL database.

## Features

- RESTful API for e-commerce operations.
- CRUD operations for managing products, categories, and tags.
- Secure connection to MySQL database using environment variables.

## Installation

1. Ensure that you have `Node.js` and `MySQL` installed on your machine.
2. Clone the repository to your local machine.
3. Run `npm install` to install the project dependencies.

## Setup

Create a `.env` file in the root directory with the following content, replacing the placeholders with your MySQL user information:


Initialize the database and tables by logging into MySQL and running: source db/schema.sql;

Seed the database with sample data by running: node seeds/index.js

Once the server is running, you can use an API client like Insomnia or Postman to test the RESTful routes.

### API Routes

Insomnia Testing Video Link:
https://www.loom.com/share/7d3d690ac47745c5a1cdbdaf924e4411?sid=7ba3848e-c00a-4aac-bfea-d2d9d6030491

- `GET /api/categories`: Fetches all categories.
- `GET /api/products`: Fetches all products.
- `GET /api/tags`: Fetches all tags.
- `POST /api/categories`: Adds a new category.
- `PUT /api/categories/:id`: Updates a category by its `id`.
- `DELETE /api/categories/:id`: Deletes a category by its `id`.

... (include other routes as necessary)

## Contributing

Contributions to this project are welcome. Please ensure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)



