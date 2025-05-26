# Ecommerce Hayroo

Project Overview
Ecommerce Hayroo is a full-stack e-commerce web platform developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). Owned by Jefferson George, this project delivers a scalable, responsive, and user-centric solution for online retail, empowering small and medium-sized enterprises (SMEs) to manage products, process transactions, and connect with customers effectively. With an open-source approach, it offers a cost-efficient, customizable alternative to traditional e-commerce platforms, featuring an intuitive interface for users to browse, purchase, and track orders, alongside a robust admin dashboard for platform oversight.
Features

Secure Authentication: User registration and login with JWT-based security and role-based access (user/admin).
Product Management: Admin tools to create, edit, or remove product listings, organized by categories for streamlined browsing.
Shopping Cart: Interactive cart allowing users to add/remove items, update quantities, and view real-time cost totals.
Order Processing: Efficient checkout system with order tracking and database storage.
Payment System: Secure transactions via Stripe API, with backend payment verification.
Admin Dashboard: Comprehensive interface for managing users, analyzing orders, and overseeing inventory.
Responsive Interface: Optimized for desktops, tablets, and mobile devices.

Technologies Used

Frontend:
React.js: Dynamic, responsive UI.
Redux: Client-side state management.
Axios: API communication.


Backend:
Node.js: Server-side runtime.
Express.js: RESTful API framework.
MongoDB: NoSQL database.
Mongoose: MongoDB ODM.
JWT: Authentication.
Stripe API: Payment processing.


Tools:
Git: Version control.
npm: Dependency management.
ESLint: Code quality.
Prettier: Code formatting.



Installation
Prerequisites

Node.js (v16+)
MongoDB (local or MongoDB Atlas)
Stripe account (for payment testing)
Git

Steps

Clone the Repository:
git clone https://github.com/jefferson404/ecommerce-hayroo.git
cd ecommerce-hayroo


Install Dependencies:

Backend:cd server
npm install


Frontend:cd ../client
npm install




Configure Environment Variables:

Create server/.env:MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
PORT=5000


Create client/.env.local:REACT_APP_API_URL=http://localhost:5000




Start MongoDB:

Ensure MongoDB is running.


Run the Application:

Backend:cd server
npm run dev


Frontend:cd ../client
npm start




Access the Platform:

Frontend: http://localhost:3000
Backend API: http://localhost:5000



Usage

Customers:
Sign up or log in to explore products.
Add items to the cart, checkout using Stripe, and track orders.


Admins:
Access the admin dashboard with admin credentials.
Manage products, view order analytics, and administer user accounts.



Project Structure

client/:
src/components/: UI components.
src/pages/: Pages (e.g., Home, Cart).
src/redux/: Redux configuration.


server/:
routes/: API routes.
models/: Mongoose schemas (User, Product, Order).
controllers/: Business logic.
middleware/: Authentication and error handling.



Contributing
Contributions are encouraged! To contribute:

Fork the repository.
Create a branch (git checkout -b feature/your-feature).
Commit changes (git commit -m "Add feature").
Push (git push origin feature/your-feature).
Submit a pull request with a clear description.

Adhere to ESLint and Prettier standards and include tests where applicable.
License
Licensed under the MIT License. See LICENSE for details.
Contact
For inquiries, contact:

Jefferson George: jeffersongeorge404@gmail.com


