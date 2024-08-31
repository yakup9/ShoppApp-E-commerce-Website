### ShoppApp - E-commerce Website

ShoppApp is a fully functional e-commerce platform developed using Node.js. It offers a seamless shopping experience with various features tailored to both customers and administrators.

#### Features

- **User Authentication**: Secure login and registration system with session management.
- **Product Management**: Add, edit, delete, and display products with categories and tags.
- **Shopping Cart**: Dynamic cart system allowing users to add, remove, and update items.
- **Order Management**: Complete order processing from checkout to payment.
- **Admin Dashboard**: Manage users, products, and orders efficiently.
- **Responsive Design**: Fully responsive layout for an optimal experience on all devices.
- **RESTful API**: API endpoints for various functionalities to support frontend and backend interactions.

#### Technologies Used

- **Node.js**: Backend server and application logic.
- **Express.js**: Web framework for routing and middleware management.
- **MongoDB**: Database for storing user data, product information, and orders.
- **Passport.js**: User authentication with secure login strategies.
- **Stripe API**: Payment processing for order transactions.
- **EJS**: Templating engine for server-side rendering of HTML pages.
- **Bootstrap**: Frontend framework for responsive design and styling.

#### Getting Started

1. **Clone the repository**:
   ```
   git clone https://github.com/yakup9/shoppapp-e-commerce-website.git
   ```
2. **Install dependencies**:
   ```
   cd shoppapp
   npm install
   ```
3. **Set up environment variables**:
   Create a `.env` file in the root directory and configure the necessary environment variables:
   ```
   MONGODB_URI=your_mongodb_uri
   STRIPE_SECRET_KEY=your_stripe_secret_key
   SESSION_SECRET=your_session_secret
   ```

4. **Run the application**:
   ```
   npm start
   ```
   The app will be running at `http://localhost:3000`.

#### Contributing

Feel free to fork this repository and submit pull requests. For significant changes, please open an issue first to discuss what you would like to change.

#### License

This project is licensed under the MIT License.
