# AirBNB Clone Project

This project is a clone of the popular room rental website, AirBNB. It is designed to allow users to list properties, search for accommodations, and make bookings. The application is built using **Next.js** for the frontend and **NestJS** for the backend.

## Features

- **Property Listings**: Users can list rooms or entire homes for rent.
- **Search Functionality**: Allows users to search for properties based on location, availability, and price.
- **Booking System**: Users can book properties and manage their reservations.
- **User Authentication**: Includes signup, login, and authentication features.
- **Reviews**: Users can leave reviews for properties they have stayed at.
- **Responsive Design**: Optimized for mobile and desktop devices.
  
## Tech Stack

### Frontend

- **Next.js**: A React framework for building fast and SEO-friendly web applications.
  - **Pages**: Dynamic routing is handled by the Next.js pages.
  - **API Routes**: Some API routes are handled within the Next.js framework for client-server interaction.
  - **SSR/SSG**: Server-side rendering and static site generation are used to optimize performance and SEO.

### Backend

- **NestJS**: A progressive Node.js framework for building efficient and scalable server-side applications.
  - **TypeORM**: Used for managing database connections and operations.
  - **REST API**: The backend exposes a RESTful API to handle all user, property, and booking data.
  - **JWT Authentication**: JSON Web Tokens are used to manage authentication and authorization.
  - **PostgreSQL**: The primary database used to store user, property, and booking data.

## Installation

### Prerequisites

- Node.js
- npm or yarn
- PostgreSQL

### Steps to run the project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/airbnb-clone.git

2. Install dependencies for the frontend and backend:
   * Navigate to the frontend directory
   ```bash
   cd frontend
   npm install
   ```

   * Navigate to the backend directory
   ```bash
   cd backend
   npm install
   ```
3. Set up environment variables:
   * Create a .env file in the backend directory with the following variables:
   ```env
   DATABASE_URL=your_postgresql_connection_string
   JWT_SECRET=your_jwt_secret
   ```  
  * For the frontend, create a .env file with API URLs and other necessary config.

4. Run the database:
    ![image](https://github.com/user-attachments/assets/2fc7eb90-b97b-48cb-bdeb-08842fa220f7)
   Start your database server locally or use a hosted solution.

5. Run the frontend and backend:
   * Start the backend server
   ```bash
   npm run start:dev
   ```
   * Start the frontend server
   ```bash
   npm run dev
   ```

6. Access the application:
   Open your browser and navigate to http://localhost:3000.

### Contributing
   Feel free to open issues or submit pull requests. We welcome all contributions to improve this project.
