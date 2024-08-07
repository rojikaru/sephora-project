# Online Perfumery Store

This project is an online perfumery store built with ASP.NET Core REST API backend and React-TypeScript frontend. It showcases a modern web application architecture using best practices and popular libraries.

## Features

- **ASP.NET Core REST API**: Robust and scalable backend
- **React-TypeScript**: Type-safe frontend built with Vite for fast development
- **Material-UI (MUI)**: Sleek and responsive UI components
- **Redux**: State management for React
- **Entity Framework Core**: ORM for database operations
- **Ardalis Clean Architecture**: Organized and maintainable codebase
- **JWT Authentication**: Secure user authentication
- **Google OAuth**: Easy sign-in with Google accounts
- **Formik & Yup**: Form handling and validation
- **Axios**: HTTP client for API requests
- **Postgres**: Easy-to-use & well-performing database

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/) (v14 or later)
- [PostgreSQL](https://www.postgresql.org/) (or another compatible database)

## Getting Started

### Backend Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/perfumery-store.git
   cd perfumery-store/backend
   ```

2. Update the connection string in `appsettings.json` to point to your database.

3. Apply database migrations:
   ```
   dotnet ef database update
   ```

4. Run the backend:
   ```
   dotnet run
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```
   cd ../frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file in the frontend root and add the secrets mentioned in env.ts file  

4. Start the development server:
   ```
   npm run dev
   ```

The frontend will be available at `http://localhost:5173`.

## Authentication

The application uses JWT for authentication. To authenticate:

1. Register a new user or log in with existing credentials.
2. Use the returned JWT token in the `Authorization` header for subsequent requests.

Google OAuth is also available for easy sign-in.

## API Documentation

API documentation is available in swagger menu when running the backend in development mode or in README.md in sephora-backend folder.
