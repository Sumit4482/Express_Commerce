# Express_Commerce 🛒

Express_Commerce is a simple e-commerce API built using Node.js and Express.js. It provides endpoints for managing products, shopping carts, orders, and seller inventory.

## Features

📦 **Product Management**: Retrieve a list of available products, view details of a specific product, and search for products based on certain criteria.

🛒 **Shopping Cart**: Add products to the shopping cart, view the contents of the cart, and remove products from the cart.

📝 **Order Management**: Create orders by processing the checkout, view a list of all orders, and retrieve details of specific orders.

👩‍💼 **Seller Inventory**: Add new products to the inventory, update information for existing products, and remove products from the inventory.

## Endpoints

### Product Requests

- `GET /products`: Retrieve a list of available products.
- `GET /products/{id}`: Retrieve details of a specific product.
- `GET /products/search`: Search for products based on certain criteria.
- `POST /products`: Add a new product to the inventory.
- `PUT /products/getbyid/{id}`: Update information for a specific product.
- `DELETE /products/{id}`: Remove a product from the inventory.

### Shopping Cart Requests

- `GET /cart`: Retrieve the contents of the shopping cart.
- `POST /cart/add`: Add a product to the shopping cart.
- `DELETE /cart/{id}`: Remove a product from the shopping cart.
- `POST /cart/checkout`: Process the checkout and create an order.

### Order Requests

- `GET /orders`: Retrieve a list of all orders.
- `GET /orders/{id}`: Retrieve details of a specific order.
- `DELETE /orders/{id}`: Cancel a specific order.

## Adding a New Endpoint

To add a new endpoint to the Express_Commerce API, follow these steps:

1. Define the route and HTTP method in the appropriate route file (e.g., `productRoutes.js`, `cartRoutes.js`, etc.).
2. Create a corresponding controller function in the `controllers` directory to handle the logic for the new endpoint.
3. Implement any necessary services or helper functions in the `services` directory.
4. Test the new endpoint thoroughly to ensure it functions as expected.
5. Update the `README.md` file to document the new endpoint, including its route, purpose, and any required parameters or payloads.

<img src="https://i.redd.it/0okcur07kjga1.jpg" width="400">
