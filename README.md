# Backend README

This project serves as the backend for the commission plan simulator. It provides APIs for managing orders, products, commissions, and calculating total commissions for staff members.

## Features

- **Order Management**: Create, read, update, and delete orders.
- **Product Management**: CRUD operations for products.
- **Commission Calculation**: Calculate total commissions for staff members based on product sales.
- **Database Integration**: Uses MongoDB as the database for storing orders, products, and commissions.
- **RESTful APIs**: Provides RESTful endpoints for interacting with orders, products, and commissions.

## Setup Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/mbaah80/commission-stimulator-api.git
    ```

2. Navigate to the backend directory:

    ```bash
    cd api
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Run the Docker Compose setup:

    ```bash
    docker-compose up
    ```

5. Access the backend APIs at `http://localhost:8000`.

## APIs

### Orders

- **GET /orders**: Fetch all orders.
- **GET /orders/:id**: Fetch a specific order by ID.
- **POST /orders**: Create a new order.
- **PUT /orders/:id**: Update an existing order.
- **DELETE /orders/:id**: Delete an existing order.

### Products

- **GET /products**: Fetch all products.
- **GET /products/:id**: Fetch a specific product by ID.
- **POST /products**: Create a new product.
- **PUT /products/:id**: Update an existing product.
- **DELETE /products/:id**: Delete an existing product.

### Commission

- **POST /commission/calculator**: Calculate total commissions for a staff member.
- **GET /commission**: Fetch all commissions.
- **GET /commission/:id**: Fetch a specific commission by ID.
- **POST /commission**: Create a new commission.
- **PUT /commission/:id**: Update an existing commission.

- **DELETE /commission/:id**: Delete an existing commission.
- **GET /commission/product/:productId**: Fetch all commissions for a specific product.


## Learn More

To learn more about Docker Compose, take a look at the following resources:

---------------------------------------------------------------------------------------------------------------------------

# Frontend README

This project is a commission plan simulator built using [Next.js](https://nextjs.org/) and [Shopify Polaris](https://polaris.shopify.com/) for the UI components.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/mbaah80/commission-stimulator-front.git
    ```

2. Navigate to the frontend directory:

    ```bash
    cd frontend
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Run the development server:

    ```bash
    npm run dev
    ```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
## Features

- **Commission Plan Configuration**: Set commission percentages for each product.
- **Filtering and Sorting**: Filter and sort products based on various criteria.
- **Bulk Actions**: Apply a specific commission percentage to multiple products at once.
- **Commission Calculation**: Calculate total commissions for a specific date range and staff member.
- **Interactive UI**: User-friendly interface with interactive components.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
