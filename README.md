# E-Commerce Store

**E-Commerce Store** is a React application offering user authentication, product shopping, Stripe-integrated purchases, and an exclusive admin dashboard for product management.

## Features
- User authentication for secure access.
- Product shopping with cart management.
- Stripe integration for seamless payments.
- Exclusive admin dashboard for managing products (create, update, delete, and feature products).
- Fully responsive design.

## Tech Stack
- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Payment Gateway**: Stripe

## Dependencies
### Core Dependencies
- **bcryptjs**: For hashing passwords securely.
- **cloudinary**: For managing and storing images.
- **cookie-parser**: For parsing cookies used in authentication.
- **dotenv**: For managing environment variables securely.
- **express**: A web application framework for handling routes and API requests.
- **ioredis**: For caching and session management.
- **jsonwebtoken**: For secure authentication via tokens.
- **mongoose**: An ODM (Object Data Modeling) library for MongoDB, used to interact with the database.
- **stripe**: For handling payment processing.

### DevDependencies
- **nodemon**: Automatically restarts the server when file changes are detected during development.

## Scripts
- **`dev`**: Runs the application in development mode with `nodemon`, allowing auto-restart on file changes.
  ```bash
  nodemon backend/server.js
  ```
- **`start`**: Runs the application in production mode.
  ```bash
  node backend/server.js
  ```
- **`build`**: Installs dependencies for both backend and frontend and builds the frontend.
  ```bash
  npm install && npm install --prefix frontend && npm run build --prefix frontend
  ```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/e-commerce-store.git
   ```
2. Navigate to the project directory:
   ```bash
   cd e-commerce-store
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the application in development mode:
   ```bash
   npm run dev
   ```

## Folder Structure
- **backend**: Contains server-side code (Express and MongoDB).
- **frontend**: Contains client-side code (React).

## License
This project is licensed under the ISC License.

