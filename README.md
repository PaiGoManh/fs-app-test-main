# Food Ordering Web App Technical Assessment (MERN Stack)

## Problems
- Authentication Fixes
Login: Return 401 Unauthorized if credentials are incorrect (currently returns 200 OK).
Registration: Return 401 Unauthorized if the user already exists (currently returns 200 OK).

- UI Enhancement
Add a zoom-in effect on hover for each menu image.
- Order UI Fix
Ensure the “-” (minus) icon in the order section maintains a consistent position when the user interacts with it (e.g., when quantity changes).


## Installation
### Prerequisites
- Node.js
- MongoDB

### Clone the Repository


## Backend Setup
Navigate to the backend directory:

```sh
cd backend

```
Install dependencies:

```sh
npm install
```

Create a .env file in the backend directory and add the following:

```sh
JWT_SECRET="random#secret"
STRIPE_SECRET_KEY=" Add Your secret key "
```

Start the backend server:

```sh
npm run server
```
## Frontend Setup
Navigate to the frontend directory:

```sh

cd frontend
```

Install dependencies:
```sh

npm install
```

Start the frontend server:
```sh

npm run dev
```

## Admin App Setup

Navigate to the admin directory:
```sh

cd admin
```

Install dependencies:

```sh
npm install
```

Start the admin app :
```sh
npm run dev
```

## Usage
Access the customer-facing app at http://localhost:5173.
Access the admin app at http://localhost:5174.
Register as a new user or log in with existing credentials.
Browse the menu, add items to the cart, and place an order.
Pay using dummy visa card
Use the admin panel to manage orders, menu items.


## API Documentation
The API endpoints for the backend can be documented using tools like Postman or Swagger. Include endpoints for user authentication, menu items, orders, and more.





