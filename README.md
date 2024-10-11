# KeWarung API Testing

This repository contains the Postman collection for API testing of the **KeWarung** project.

## How to Use the Collection

1. **Download Collection**: Download the Postman collection from this repository (`testAPI-KeWarung.postman_collection.json`).
2. **Import to Postman**: Open Postman, click the **Import** button, and select the downloaded `.json` file.
3. **Run Tests**: You can run the collection directly in Postman to test the API endpoints.

## API Endpoints Tested

- `GET /products`: Retrieve a list of products.
- `POST /products`: Add a new product to the inventory.
- `PUT /products/{id}`: Update product details.
- `DELETE /products/{id}`: Delete a product from the inventory.

## Prerequisites

- Install [Postman](https://www.postman.com/downloads/).
- Ensure that the API server is running locally or is accessible online for the tests to work.

## Additional Notes

- Make sure to configure environment variables for the API base URL or authentication tokens if required.
- The environment configuration can also be included by importing the provided environment file in the repository.
