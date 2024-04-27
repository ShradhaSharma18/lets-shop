# Let's Connect Shop App

Welcome to Let's Connect Shop, an e-commerce application built using React, Node.js, and Express. This app allows users to browse products, add them to their cart, and checkout. It includes token-based authentication, user session management using cookies, and a user database to store user information and cart items.

## Features

- **Token-based Authentication**: Secure user authentication using JSON Web Tokens (JWT).
- **User Session Management**: User sessions are maintained using cookies, ensuring users remain logged in even after refreshing the page.
- **User Database**: User information and cart items are stored in a database for persistence.
- **Product Item Page**: Browse through a list of products and view detailed information about each product.
- **Cart Page**: Add products to the cart, view the items in the cart, and update or remove items as needed.
- **Buy Now Page**: Proceed to checkout and finalize the purchase (payment functionality not implemented yet).
- **SignIn Page** :  SignIn page to login to the app
- **SignUp Page** : SignUp page to register teh user to the data base 

## Technologies Used

- **Frontend**: React , Redux , Tailwind CSS , Material-UI , Cookies
- **Backend**: Node.js, Express.Js , 
- **Database**: MongoDB , mongoose

## Getting Started

### Prerequisites

- Node.js installed on your machine
- MongoDB installed and running (or any other database of your choice)

### Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd lets-connect-shop
   ```

3. Install dependencies for both frontend and backend:

   ```
   cd client
   npm install
   cd ../server
   npm install
   ```

4. Set up environment variables:
   
   Create a `.env` file in the `server` directory and add the following environment variables:
   ```
   PORT=5000
   MONGODB_URI=<your-mongodb-uri>
   JWT_SECRET=<your-jwt-secret>
   ```

5. Start the backend server:

   ```
   cd server
   npm start
   ```

6. Start the frontend development server:

   ```
   cd client
   npm start
   ```

7. Access the application in your browser at `http://localhost:3000`.

## Folder Structure

- **client**: Contains the React frontend code.
- **server**: Contains the Node.js backend code.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request with any improvements or features.

Thank You for reading the readme 
