# Edunet Foundation, in collaboration with EY GDS & AICTE 

# Internship on Full Stack Web Development with MERN.


FINAL WEEK SUBMISSION


# 🎉 Auction Bidding System

Welcome to the **Auction Bidding System**! This MERN application is designed to manage auctions, bids, and users.

The goal of this project is to develop a secure and user-friendly crowdfunding platform using React for the front end 
and ExpressJS for the back end, addressing the challenges of user authentication, project management, and payment processing.
The platform will enable project creators to easily launch and manage their campaigns while allowing backers to discover, support, 
and engage with innovative ideas. Key features will include a robust search and filtering system, real-time communication between 
creators and backers, and comprehensive analytics for campaign performance, all while ensuring data security and compliance with 
financial regulations to foster trust and transparency in the crowdfunding process.

#### It features:

-   **Backend**: Built with **Node.js** and **Express**.
-   **Frontend**: Developed using **React** with **Vite** for the build tool.
-   **Styling**: Styled with **Tailwind CSS**.
-   **Database**: Uses **MongoDB** for data storage.
-   **Authentication**: Managed with **JWT** (JSON Web Tokens).
-   **Password Security**: Handled with **bcrypt** for hashing passwords.

## 📂 Directory Structure

```plaintext
project/
├── backend/
│   ├── config/
│   │   └── db.js            # Database configuration and connection setup
│   ├── controllers/
│   │   ├── auctionController.js  # Business logic for auction management
│   │   ├── bidController.js      # Business logic for bid management
│   │   └── userController.js     # Business logic for user management
│   ├── middleware/
│   │   └── authMiddleware.js     # Middleware for authentication
│   ├── models/
│   │   ├── AuctionItem.js        # Mongoose schema for auction items
│   │   ├── Bid.js                # Mongoose schema for bids
│   │   └── User.js               # Mongoose schema for users
│   ├── routes/
│   │   ├── auctionRoutes.js      # API routes for auction-related requests
│   │   ├── bidRoutes.js          # API routes for bid-related requests
│   │   └── userRoutes.js         # API routes for user-related requests
│   └── server.js                 # Entry point for the backend server
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── AuctionItem.jsx   # Component for displaying auction items
│   │   │   ├── BidForm.jsx       # Component for submitting bids
│   │   │   ├── Home.jsx          # Home page component
│   │   │   ├── NavBar.jsx        # Navigation bar component
│   │   │   └── Signup.jsx        # Component for user registration
│   │   ├── contexts/
│   │   │   └── AuthContext.jsx   # Context for managing authentication state
│   │   ├── App.jsx               # Main application component
│   │   ├── index.jsx             # Entry point for the React app
│   │   └── main.jsx              # Renders the React app
│   ├── tailwind.config.js        # Tailwind CSS configuration
│   ├── vite.config.js            # Vite configuration for the frontend build
│   └── index.html                # Main HTML file for the frontend
└── README.md                     # This file
```

## 🏗️ Main Directories and Files

### Backend (`backend/`)

-   **`config/`**: Contains configuration files such as `db.js` for setting up the database connection.
-   **`controllers/`**: Implements business logic for different aspects of the application:
    -   `auctionController.js`: Handles auction-related operations.
    -   `bidController.js`: Manages bid-related logic.
    -   `userController.js`: Manages user-related logic.
-   **`middleware/`**: Includes middleware functions like `authMiddleware.js` for authentication and authorization.
-   **`models/`**: Defines data models using Mongoose:
    -   `AuctionItem.js`: Schema for auction items.
    -   `Bid.js`: Schema for bids.
    -   `User.js`: Schema for users.
-   **`routes/`**: Defines API routes:
    -   `auctionRoutes.js`: Routes for auction-related API endpoints.
    -   `bidRoutes.js`: Routes for bid-related API endpoints.
    -   `userRoutes.js`: Routes for user-related API endpoints.
-   **`server.js`**: Entry point for starting the backend server and connecting to the database.

### Frontend (`frontend/`)

-   **`src/`**: Source code for the React application:
    -   **`components/`**: Contains React components for various parts of the UI.
        -   `AuctionItem.jsx`: Displays auction items.
        -   `BidForm.jsx`: Form for placing bids.
        -   `Home.jsx`: Home page component.
        -   `NavBar.jsx`: Navigation bar component.
        -   `Signup.jsx`: User registration component.
    -   **`contexts/`**: Contains context providers like `AuthContext.jsx` for managing user authentication state.
    -   **`App.jsx`**: Main component that sets up routing and the overall layout of the application.
    -   **`index.jsx`**: Entry point that renders `App.jsx`.
    -   **`main.jsx`**: Initializes the React application.
-   **`tailwind.config.js`**: Configuration file for Tailwind CSS styling.
-   **`vite.config.js`**: Configuration file for Vite, used for frontend build and development.
-   **`index.html`**: Main HTML file that serves as the entry point for the frontend application.

## 🚀 Getting Started

### Prerequisites

-   **Node.js** (v14 or later)
-   **npm** (v6 or later) or **yarn**

### Installation

#### Backend

1. Navigate to the `backend` directory:

    ```bash
    cd backend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables:
    - Create a `.env` file in the `backend` directory with the following content:
        ```plaintext
        PORT=5000
        MONGODB_URI=your_mongo_uri
        JWT_SECRET=your_jwt_secret
        ORIGIN=http://localhost:5173 or url of frontend
        ```

#### Frontend

1. Navigate to the `frontend` directory:

    ```bash
    cd frontend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables:
    - Create a `.env` file in the `frontend` directory with the following content:
        ```plaintext
        TARGET=http://localhost:5000 or url of backend
        ```

## 🏃‍♂️ Running the Project

### Backend

1. Start the backend server:

    ```bash
    npm run dev
    ```

    The backend will run on [http://localhost:5000](http://localhost:5000).

### Frontend

1. Start the frontend development server:

    ```bash
    npm run dev
    ```

    The frontend will run on [http://localhost:5173](http://localhost:5173).

-----------------------------------------------------------------------------------------

# Details 

Date: 09/02/2025

Name : Chaudhari Harsh Nitin

AICTE Student ID: STU66c049f07aac21723877872

AICTE Internship ID: INTERNSHIP_173892172667a5d6fed4b6a

Internship Name : Full Stack Web Development with MERN (6-week Internship, commencing from 10th February 2025 to 21st March 2025)

