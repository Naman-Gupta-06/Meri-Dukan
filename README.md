
# MeriDukan Web Application

This web application is built using MERN stack. It allows users to browse and purchase products similar to the Amazon website. 

## Features

- User authentication (signup and login)
- Browse products by category
- Add products to cart
- Checkout and make payments using Stripe
- View order history and order details
- email confirmation upon order placement
- Enabled guest users to buy products without logging in

## Installation

To install the application, follow these steps:

1. Clone the repository
2. Install dependencies using `npm install`
3. Create a `.env` file and add environment variables as per the example `.env.example` file
4. Start the server using `npm start`

## APIs

The following APIs are available:

- `/api/users`: User authentication APIs for signup and login
- `/api/products`: APIs for getting product details and adding products to cart
- `/api/orders`: APIs for creating and fetching orders

## Technologies Used

- React.js for frontend
- Node.js and Express.js for backend
- MongoDB for database
- Stripe for payment integration

## Credits

- The design and layout of the application is inspired by the Amazon website.
- Icons used in the application are sourced from Font Awesome.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
