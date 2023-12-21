# se3355_assignment2

# Project Title

Description: This project is a [Here is my se3355 assignment2 with using Flask and for the database Sqlite].

## Data Model

The data model for the project is as follows:

- **Product**
  - `id`: The unique identifier for the product (Primary Key).
  - `title`: The name of the product.
  - `description`: A detailed description of the product.
  - `price`: The price of the product.
  - `city`: The city where the product is located.
  - `category`: The category to which the product belongs.
  - `image_url`: The URL of the product image.

- **Category**
  - `id`: The unique identifier for the category (Primary Key).
  - `name`: The name of the category.
  - `product_count`: The number of products in this category.

The database schema is implemented using SQLite and defined in `initialize_db.py` using the SQLite.

## Assumptions
- My application is developed with Flask. It is structured around the layout of Sahibinden, including a homepage, search results, and details. Each product card is designed to display an image, a description, the price and address . A search feature is integrated to query across all product attributes. For responsive design i used Bootstrap framework.
- All users have browsers that support JavaScript.
- Product information is regularly updated.
- No session management or authentication system is required for users.

## Issues

Some issues encountered during the development of the project:

- Optimization of the search functionality: Performance testing with large data sets is needed.
- Responsive design: Layout disruptions have been observed on some mobile devices and need to be corrected.

## DEPLOYMENT

I deployed the web app to Azure Web Services. 
[Deployed at](https://se3355assignment2.azurewebsites.net/)
