# tiny-crm-backend
"# backend-crm-xeno" 

# Mini CRM Backend

This is the backend application for the Mini CRM project, built using Node.js, Express, MongoDB, and RabbitMQ. It provides APIs for data ingestion, audience creation, campaign management, and tracking delivery statuses.

## Features

- APIs for ingesting customer and order data
- Create and manage audiences based on flexible rules
- Send campaigns to selected audiences
- Track and update delivery statuses using RabbitMQ

## Tech Stack

- Node.js
- Express
- MongoDB with Mongoose
- RabbitMQ

## API endpoints through Postman

### Customer :

GET: https://tiny-crm-backend.onrender.com/api/customer

POST: https://tiny-crm-backend.onrender.com/api/customer

(example test case)

body (json) :

{

    "name": "John Doe",
    
    "email": "john@example.com",
    
    "phone": "1234567890"
    
}

### Order :

GET: https://tiny-crm-backend.onrender.com/api/order

POST: https://tiny-crm-backend.onrender.com/api/order

(example test case)

body:

{

    "customerId": "666927586080476cefd62576",
    
    "product": "Laptop",
    
    "amount": 50000
    
}
