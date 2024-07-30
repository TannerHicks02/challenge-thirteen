# E-Commerce Back End

This project is a back end for an e-commerce website, built using the latest technologies. It includes a functional Express.js API and uses Sequelize to interact with a PostgreSQL database.

## User Story

```md
As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies so that my company can compete with other e-commerce companies.
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the PostgreSQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Usage
Use Insomnia, Postman, or any other API client to test the API routes.

## API Routes
* Categories
    * GET /api/categories
    * GET /api/categories/:id
    * POST /api/categories
    * PUT /api/categories/:id
    * DELETE /api/categories/:id
* Products
    * GET /api/products
    * GET /api/products/:id
    * POST /api/products
    * PUT /api/products/:id
    * DELETE /api/products/:id
* Tags
    * GET /api/tags
    * GET /api/tags/:id
    * POST /api/tags
    * PUT /api/tags/:id
    * DELETE /api/tags/:id