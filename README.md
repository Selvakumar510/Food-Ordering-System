# Restaurant Food Ordering Management System

A comprehensive and modern food ordering platform built with the **MERN stack (MongoDB, Express.js, React, Node.js)**. The application provides restaurant management, menu management, online ordering, payment processing, real-time order tracking, advanced search, and business analytics.

## Features

### Core Functionality

- **Restaurant Management** - Create, view, update, and manage restaurants.
- **Menu Management** - Add, update, delete, and manage menu items.
- **Order Processing** - Manage customer orders and order status.
- **Payment Integration** - Secure payment processing using Stripe.
- **User Authentication** - Secure authentication using Auth0.
- **Restaurant Dashboard** - Manage restaurant information, menus, and orders.

### Advanced Features

- **Business Analytics Dashboard** - View revenue, orders, customer insights, and performance metrics.
- **Advanced Search** - Search restaurants using multiple filters.
- **Order Tracking** - Track orders throughout the complete order lifecycle.
- **API Documentation** - Provides structured API documentation for backend services.
- **Performance Monitoring** - Monitor application and system performance.
- **Real-Time Updates** - Display live order status and notifications.

### User Experience

- Responsive and mobile-friendly design.
- Modern UI using Shadcn/ui and Tailwind CSS.
- Dark and light mode support.
- Toast notifications.
- Interactive dashboards and charts.
- Advanced filtering and sorting.
- Clean and user-friendly navigation.

---

# Technology Stack

## Frontend

- **React 18.2.0** - Frontend library
- **TypeScript 5.3.3** - Type-safe development
- **Vite** - Development server and build tool
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/ui** - UI component library
- **React Query** - Server-state management
- **React Router** - Client-side routing
- **React Hook Form** - Form management
- **Zod** - Schema validation
- **Auth0** - Authentication and authorization
- **Stripe** - Payment processing
- **Lucide React** - Icon library

## Backend

- **Node.js** - JavaScript runtime
- **Express.js** - Backend web framework
- **TypeScript** - Type-safe backend development
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **Stripe** - Payment processing
- **Auth0** - Authentication middleware
- **Cloudinary** - Image upload and management
- **Multer** - File upload handling
- **Express Validator** - Request validation
- **CORS** - Cross-origin resource sharing

## Development Tools

- ESLint
- Prettier
- Nodemon
- Concurrently
- Git
- GitHub

---

# Project Structure

```text
food-ordering/
│
├── food-ordering-frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   ├── EnhancedOrdersTab.tsx
│   │   │   ├── OrderStatusDetail.tsx
│   │   │   ├── AdvancedSearchBar.tsx
│   │   │   └── ...
│   │   │
│   │   ├── pages/
│   │   │   ├── HomePage.tsx
│   │   │   ├── ManageRestaurantPage.tsx
│   │   │   ├── AnalyticsDashboardPage.tsx
│   │   │   ├── SearchPage.tsx
│   │   │   ├── OrderStatusPage.tsx
│   │   │   └── ...
│   │   │
│   │   ├── api/
│   │   ├── auth/
│   │   ├── config/
│   │   ├── forms/
│   │   ├── layouts/
│   │   ├── lib/
│   │   ├── types.ts
│   │   └── AppRoutes.tsx
│   │
│   ├── package.json
│   └── vite.config.ts
│
├── food-ordering-backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── index.ts
│   │
│   ├── package.json
│   └── .env.example
│
└── README.md
```

---
 
