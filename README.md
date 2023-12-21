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

The database schema is implemented using SQLite and defined in `models.py` using the SQLAlchemy ORM.

## Assumptions

- All users have browsers that support JavaScript.
- Product information is regularly updated.
- No session management or authentication system is required for users.

## Issues

Some issues encountered during the development of the project:

- Optimization of the search functionality: Performance testing with large data sets is needed.
- Responsive design: Layout disruptions have been observed on some mobile devices and need to be corrected.

## Installation

To run the project on your local machine, follow these steps:

```bash
git clone https://github.com/yourUsername/yourProjectName.git
cd yourProjectName
pip install -r requirements.txt
flask run
