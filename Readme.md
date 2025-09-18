
# Dwellify - Full-Stack Home Rentals Application

Dwellify is a **full-stack home rental web application** built using **React**, **Redux**, **Node.js**, **MongoDB**, **JWT**, and **Material UI**. Users can register, log in, view property listings, manage their wishlists, and create new listings. Admins have the ability to manage bookings, properties, and user data.

## Key Features

### User Features:
- **Sign Up & Log In**: Secure user authentication using **JWT** and **Bcrypt** for password hashing.
- **Create Listings**: Users can create new property listings with detailed information such as price, location, description, etc.
- **Select & Unselect Options**: Choose property features (e.g., pool, pet-friendly, parking) to refine listing criteria.
- **Drag & Drop Photos**: Upload, delete, and manage property images with drag-and-drop functionality.
- **Create Booking**: Users can book properties using an interactive **calendar**.
- **Fetch Property Feed by Category**: Browse properties categorized by type, e.g., apartments, houses, etc.
- **Search by Keyword**: Users can search for properties by keywords or location.
- **Add/Remove from Wishlist**: Easily manage favorite properties by adding or removing them from a personal wishlist.
- **Image Upload to MongoDB**: Upload and store images locally and save them to **MongoDB** for persistence.

### Admin Features:
- **Manage Bookings**: Admins can view and manage all bookings made by users.
- **Manage Properties**: Admins can view, edit, or delete property listings.
- **Manage Users**: Admins can view and manage user data, including status updates and account actions.

## Technologies Used

### Frontend:
- **React**: For building the dynamic user interface.
- **Redux**: For state management across the application.
- **Material UI**: For pre-built UI components and responsive design.
- **Sass (SCSS)**: For modular and maintainable styling.

### Backend:
- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web framework for building RESTful APIs.
- **MongoDB**: NoSQL database for storing user and property data.
- **Mongoose**: MongoDB object modeling and schema definition.
- **JWT (JSON Web Token)**: Used for user authentication and session management.
- **Bcrypt**: For hashing and securely storing user passwords.


