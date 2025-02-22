Setup Instructions
Prerequisites:
Node.js (v16 or later)
MongoDB
npm (Node Package Manager)

Installation:
Clone the repository
Install all depencieas
Set up environment variables
Start

Authentication:
Register: 
POST /api/register
Login: 
POST /api/login

Products
Create Product: POST /api/products
Get Products: GET /api/products
Update Product: PUT /api/products/:id
Delete Product: DELETE /api/products/:id

Database Schema:
Users Collection: Stores user details.
Products Collection: Contains product information.
Suppliers Collection: Holds supplier details.

Security:
Authentication: Uses JWT tokens.
Authorization: Restricts access based on roles.