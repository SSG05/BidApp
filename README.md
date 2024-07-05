# Bidding Project

This is a React-based e-commerce application that includes various features such as user authentication, product management, order management, and supplier management.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Run the application:**
    ```bash
    npm start
    ```

    The application will be available at `http://localhost:3000`.

## Usage

The application includes various routes and components that handle different functionalities. Below are some of the main routes and their purposes:

- `/` or `/home`: Home page displaying product categories and featured products.
- `/contact`: Contact us page.
- `/about`: About us page.
- `/addproduct`: Form to add a new product.
- `/addcategory`: Form to add a new category.
- `/user/register`: User registration form.
- `/user/login`: User login form.
- `/user/admin/register`: Admin registration form.
- `/user/admin/login`: Admin login form.
- `/user/deliveryperson/register`: Delivery person registration form.
- `/user/deliveryperson/login`: Delivery person login form.
- `/user/productOffers`: Display user's product offers.
- `/user/order/payment`: Form to add card details for payment.
- `/user/myorder`: Display user's orders.
- `/user/admin/allorder`: Display all orders for admin.
- `/user/admin/searchOrder`: Search for orders by admin.
- `/user/admin/assigndelivery`: Assign delivery to orders by admin.
- `/user/delivery/myorders`: Display delivery person's orders.
- `/user/supplier/register`: Supplier registration form.
- `/supplier/all`: View all suppliers.
- `/product/:productId/review/add`: Form to add a product review.
- `/product/review/fetch`: Fetch product reviews.
- `/customer/wallet`: Display user's wallet.
- `/user/verify/register`: User OTP verification.
- `/admin/product/update`: Form to update a product.
- `/admin/category/update`: Form to update a category.
- `/admin/category/all`: View all categories.

## Features

- **User Authentication:** Registration and login forms for users, admins, and delivery persons.
- **Product Management:** Add, update, and view products and categories.
- **Order Management:** View, search, and assign deliveries for orders.
- **Supplier Management:** Register and view suppliers.
- **Reviews and Ratings:** Add and view product reviews.
- **Responsive Design:** Adaptable to different screen sizes.

## File Structure

- `index.js`: Entry point of the application, setting up the React app with React Router.
- `index.css`: Global styles for the application.
- `App.js`: Main component containing routes and rendering different pages/components.


