## Shopping Cart Application

Welcome to the Shopping Cart Application! This project was completed as part of the Professional Certificate in Coding: Full Stack Development with MERN program at MIT. This application uses Strapi,a powerful Node.js headless CMS,and React for the frontend. This README provides instructions on how to setup and run this application on your local machine.

## Application Features

This Shopping Cart application allows you to:

- Add products to your shopping cart
- Reset the stock when it runs out

When a user clicks the "ReStock Products" button, a call is made to the Strapi back end specified in an input field. The result of this call is an updated list of products.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js 14.x or later
- npm 6.x or later (usually comes bundled with Node.js) or Yarn
- MongoDB/PostgreSQL/MySQL (Choose the one that your application uses)

## Setup

1. Clone the repository:
```
git clone https://github.com/<your-username>/shopping-cart-application.git
```

2. Navigate to the project folder:
```
cd shopping-cart-application
```

3. Install dependencies for the Strapi backend and React frontend. The backend and frontend folders are assumed to be named 'backend' and 'frontend' respectively:
```
cd backend && npm install
cd ../frontend && npm install
```

## Running the Application

Navigate back to the root directory and run the application:

1. Start the Strapi server:
```
cd backend && npm run develop
```

2. In a separate terminal window, start the React application:
```
cd frontend && npm start
```

Now you can visit the Strapi admin panel at http://localhost:1337/admin and the React application at http://localhost:3000.


