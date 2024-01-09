E-Commerce Backend API

Welcome to the backend API for our e-commerce site. This API serves as the foundation for managing products, orders, and users in our online store.

Introduction
This backend API is designed to support the functionality of an e-commerce website. It allows users to interact with the system by managing products, processing orders, and handling user accounts.

Getting Started
Prerequisites
Before you begin, make sure you have the following installed:

Node.js
npm or Yarn
Installation
Clone the repository:

git clone https://github.com/sitkujanos86/e-commerce-API.git

Navigate to the project directory:
cd server

Install dependencies:

npm install
or
yarn install
Usage

Authentication
To access most endpoints, you need to authenticate. Obtain an API key by contacting the administrator.

Include the API key in the Authorization header of your requests:

Authorization: YOUR_API_KEY
Endpoints
Here are some of the available endpoints:

/products

GET: Retrieve all products
POST: Add a new product

Refer to the API documentation for a complete list of endpoints and their functionalities.

Data Models
The API uses the following data models:

Product

json
Copy code
{
"id": "string",
"name": "string",
"description": "string",
"picture": link
"category": "string"
"price": "number",
}

Error Handling
The API returns standard HTTP status codes. Refer to the documentation for details on error responses.
