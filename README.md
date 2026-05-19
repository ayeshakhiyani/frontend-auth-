# Frontend - React Authentication App

## Overview
React 18 application with JWT authentication integration.

## Scripts
- `npm start` - Start development server
- `npm run build` - Create production build
- `npm test` - Run tests

## Environment Variables
- `REACT_APP_API_URL` - Backend API URL (default: http://localhost:5000/api)

## Features
- User registration and login
- JWT token management
- Protected dashboard page
- Automatic token injection in API requests
- Context-based authentication state

## Pages
- `/login` - Registration and login page
- `/dashboard` - Protected user dashboard
- `/` - Redirects to dashboard (if authenticated) or login

## Components
- `AuthContext` - Global authentication state
- `Login` - Combined signup/login form
- `Dashboard` - Protected user profile page

## Services
- `api.js` - Axios instance with JWT interceptors

## CSS Styling
- Gradient background
- Card-based layouts
- Responsive design
- Error messaging
