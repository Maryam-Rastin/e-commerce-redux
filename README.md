# E-Commerce Store

A modern e-commerce web application built with React and Redux Toolkit, providing users with a fast, responsive, and intuitive online shopping experience. The application demonstrates scalable state management, dynamic routing, and modern frontend development practices.

## Overview

E-Commerce Store is a fully responsive shopping platform designed to simulate a real-world online retail experience. Users can browse products, manage their shopping cart, and navigate seamlessly through the application using client-side routing.

The project leverages Redux Toolkit for efficient state management, ensuring a reliable and consistent user experience across the application. Built with React and modern frontend tools, this project highlights best practices in component architecture, application state management, and responsive UI design.

## Features

* Browse available products
* View detailed product information
* Add products to the shopping cart
* Remove products from the cart
* Update item quantities
* Persistent and centralized state management using Redux Toolkit
* Responsive design for desktop, tablet, and mobile devices
* Fast client-side navigation with React Router
* Clean and intuitive user interface

## Tech Stack

### Frontend

* React 19
* React Router DOM
* React Icons

### State Management

* Redux Toolkit
* React Redux

### Deployment

* GitHub Pages

## Screenshots

> Add screenshots of the application here.

## Installation

Clone the repository:

```bash
git clone https://github.com/Maryam-Rastin/e-commerce-redux.git
```

Navigate to the project directory:

```bash
cd e-commerce-redux
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The application will run locally at:

```text
http://localhost:3000
```

## Build for Production

```bash
npm run build
```

## Deploy to GitHub Pages

```bash
npm run deploy
```

## Project Structure

```text
src/
├── components/
├── pages/
├── features/
├── store/
├── routes/
├── assets/
├── App.js
└── index.js
```

## Technical Highlights

### Redux Toolkit State Management

Implemented centralized application state using Redux Toolkit to manage:

* Shopping cart data
* Product information
* User interactions
* Application-wide state updates

### Component-Based Architecture

Developed reusable React components to improve maintainability, scalability, and code organization.

### Client-Side Routing

Implemented React Router for seamless navigation and improved user experience without page reloads.

### Responsive Design

Built a mobile-first interface that adapts to different screen sizes and devices.

## Challenges & Solutions

### Challenge: Managing Shared Application State

E-commerce applications require multiple components to access and update the same data, particularly shopping cart information.

### Solution

Implemented Redux Toolkit to centralize state management, making data flow predictable and reducing unnecessary prop drilling between components.

### Challenge: Maintaining a Responsive User Experience

Users expect immediate feedback when interacting with shopping carts and product listings.

### Solution

Optimized component rendering and state updates to ensure smooth interactions and consistent UI behavior.

## Learning Outcomes

This project strengthened my understanding of:

* Redux Toolkit and modern state management
* React application architecture
* Component reusability
* Client-side routing
* Responsive web design
* Managing complex application state
* Frontend deployment workflows

## Future Improvements

* User authentication and accounts
* Product search and filtering
* Product categories
* Wishlist functionality
* Order history
* Payment gateway integration
* Backend API integration
* Inventory management
* Dark mode support

## What I Learned

Through this project, I gained hands-on experience building a scalable React application with centralized state management. I learned how Redux Toolkit simplifies state handling, how to structure larger frontend applications, and how to create responsive user interfaces that deliver a smooth shopping experience across devices.

## Author

**Maryam Rastin**

GitHub: https://github.com/Maryam-Rastin

## License

This project is available under the MIT License.
