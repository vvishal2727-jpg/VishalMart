# VishalMart

VishalMart is a multi-seller e-commerce web application built with a C++17 Drogon backend, HTML/CSS/JavaScript frontend, and PostgreSQL database.

## Main modules
- Buyer and seller registration/login with email OTP
- Product catalogue, search and category filtering
- Seller product listing and stock management
- Shopping cart, checkout, and order history
- Seller order management
- Admin user, order, and product moderation
- Product reviews and ratings

## Technology
- Frontend: HTML, CSS, JavaScript
- Backend: C++17 and Drogon
- Database: PostgreSQL (Neon-compatible)
- Build: CMake
- Deployment: Docker / Render

The AI shopping chatbot has been removed from both the frontend and backend.
Existing database environment variable names are retained so an existing deployment can be reconfigured without changing its database secret names.
