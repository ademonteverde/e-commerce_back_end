# E-Commerce Back End

## Description
This is the back end of an e-commerce website that utilizes the latest technologies, including Express.js and Sequelize, to manage categories, products, and tags.

## User Story
As a manager at an internet retail company, I want a back end for my e-commerce website using the latest technologies so that my company can compete with other e-commerce companies.

## Installation
1. Clone the repository to your local machine:

   ```
   git clone git@github.com:ademonteverde/e-commerce_back_end.git
   ```

2. Install the required dependencies:
    ```
    npm install
    ```

3. Create an environment variable file (.env) in the project root and add your MySQL database configuration:
    ```
    DB_NAME=your_database_name
    DB_USER=your_mysql_username
    DB_PASSWORD=your_mysql_password
    ```

4. To create and seed the development database, run the following command:
    ```
    npm run seed
    ```

5. Start the server with the following command:
    ```
    npm start
    ```

## API Routes
### Categories

- GET /api/categories - Get all categories.
- GET /api/categories/:id - Get a single category by ID.
- POST /api/categories - Create a new category.
- PUT /api/categories/:id - Update a category by ID.
- DELETE /api/categories/:id - Delete a category by ID.

### Products
- GET /api/products - Get all products.
- GET /api/products/:id - Get a single product by ID.
- POST /api/products - Create a new product.
- PUT /api/products/:id - Update a product by ID.
- DELETE /api/products/:id - Delete a product by ID.

###T ags
- GET /api/tags - Get all tags.
- GET /api/tags/:id - Get a single tag by ID.
- POST /api/tags - Create a new tag.
- PUT /api/tags/:id - Update a tag by ID.
- DELETE /api/tags/:id - Delete a tag by ID.

## Link to GitHub Repository:

[https://github.com/ademonteverde/e-commerce_back_end](https://github.com/ademonteverde/e-commerce_back_end)

## License

This project is licensed under the [MIT](https://github.com/ademonteverde/svg_logo_maker/blob/main/LICENSE) License.