# 🍽️ Restaurant Reservation Platform

> A modern, production-inspired restaurant reservation web application built with **React**. The project focuses on scalable frontend architecture, reusable UI components, authentication, REST API integration, state management, and responsive user experience.

---

## Overview

Restaurant Reservation Platform is a fully responsive frontend application that simulates a real-world online restaurant reservation service.

The application allows users to:

* Browse restaurants
* View detailed restaurant information
* Reserve tables
* Read customer reviews
* Submit ratings and reviews
* Authenticate securely
* Manage their profile
* Access protected pages after login

The project was originally based on an course specification and has been expanded with professional software engineering practices, modern frontend architecture, and production-ready coding standards. It combines the UI implementation from the first phase with backend integration, authentication, and protected routing introduced in the second phase.

# Demo

> Coming Soon

---

# Features

### Authentication

* Login with REST API
* JWT token authentication
* Protected routes
* Persistent authentication
* Logout functionality
* Session management

---

### Restaurant Listing

* Dynamic restaurant cards
* Restaurant availability status
* Restaurant ratings
* Restaurant categories
* Responsive card layout
* API-powered data

---

### Restaurant Details

* Complete restaurant information
* Opening & closing hours
* Address information
* Rating summary
* Customer reviews
* Review statistics

---

### Reservation System

* Table reservation form
* Date selection
* Time selection
* Guest selection
* Form validation
* Disabled submit until valid

---

### Review System

* Interactive star rating
* Multi-category ratings

Ratings include:

* Food
* Service
* Ambiance
* Overall

Additional features:

* Comment submission
* Review modal
* Live validation
* Review updates through API

---

### Customer Dashboard

* User information
* Reservation access
* Logout
* Protected content

---

### Responsive Design

Designed for:

* Desktop
* Laptop
* Tablet
* Mobile

---

# Technologies

## Frontend

* React
* React Router
* JavaScript (ES6+)
* HTML5
* CSS3

---

## State Management

* React Hooks
* Context API
* Local Storage

---

## API Integration

* REST APIs
* Fetch API
* JSON
* Authorization Headers
* JWT Authentication

---

## UI Development

* Component-Based Architecture
* Responsive Layout
* Reusable Components
* Custom Rating Components
* Modal Components
* Form Components

---

## Development Practices

* Clean Code
* Reusable Components
* Separation of Concerns
* Modular Folder Structure
* Scalable Architecture
* Maintainable Codebase

---

# Skills Demonstrated

This project showcases practical frontend engineering skills including:

* Modern React Development
* Component Architecture
* API Consumption
* Authentication Flow
* Protected Routing
* State Management
* Form Handling
* Client-side Validation
* Responsive Design
* Dynamic Rendering
* Conditional Rendering
* Custom Hooks (where applicable)
* Context API
* Local Storage Persistence
* Reusable UI Design
* Production-ready Project Structure

---

# Project Architecture

```
src/
│
├── assets/
├── components/
│   ├── Header/
│   ├── Footer/
│   ├── Card/
│   ├── Rating/
│   ├── Modal/
│   ├── ReservationForm/
│   └── ProtectedRoute/
│
├── pages/
│   ├── Home/
│   ├── Restaurant/
│   ├── Login/
│   └── Customer/
│
├── context/
├── hooks/
├── services/
├── utils/
├── styles/
├── App.jsx
└── main.jsx
```

---

# API Integration

The application communicates with a REST backend to perform operations such as:

* User Login
* Restaurant Listing
* Restaurant Details
* Review Submission
* Authentication Validation

## Authenticated requests include authorization tokens to access protected endpoints.

# Validation

The application performs client-side validation for:

* Login form
* Reservation form
* Review submission
* Required fields
* Rating completion
* Date restrictions
* Seat limits

---

# Performance Considerations

* Reusable UI components
* Efficient rendering
* Minimal component duplication
* Organized state management
* Clean routing structure

---

# Future Improvements

* Search functionality
* Restaurant filtering
* Pagination
* Dark mode
* Favorites
* Reservation history
* Profile editing
* Image optimization
* Skeleton loaders
* Unit testing
* End-to-end testing
* CI/CD pipeline
* Docker deployment
* TypeScript migration

---

# Learning Outcomes

During this project I practiced and strengthened my understanding of:

* Building scalable React applications
* Designing reusable UI systems
* Integrating RESTful APIs
* Authentication and authorization
* React Router
* Context API
* Dynamic rendering
* Form validation
* Responsive web development
* Frontend project architecture
* Clean software engineering practices

---

# Installation

```bash
git clone https://github.com/yourusername/restaurant-reservation-platform.git

cd restaurant-reservation-platform

npm install

npm run dev
```

---

# License

This project was developed for educational purposes and serves as a portfolio project demonstrating modern frontend development skills.
