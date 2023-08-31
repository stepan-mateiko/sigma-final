# sigma-final-task

## Description

This project is a web application that serves as an internet store. Users can browse and select products, place orders, and view order history. This project demonstrates the integration of React for the front end, Node.js for the back end, and MongoDB (MongoDB Atlas) for the database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)

## Installation

To set up and run this project locally, follow these steps:

### Prerequisites

- Node.js and npm installed on your local machine.
- MongoDB Atlas account for database access.

### Clone the Repository

```bash
git clone https://github.com/stepan-mateiko/sigma-final.git
```

### Install Dependencies

In both the client and server directories, run:

```bash
npm install
```

### Configuration

#### Server Configuration

1. Create a `.env` file in the server directory.

2. At MongoDB Atlas go to the cluster page and get connection string
   `https://cloud.mongodb.com/v2/64d95fe6e6c514140e8b3734#/overview`

3. Add your MongoDB Atlas connection string to the `.env` file:

```env
MONGODB_URI=your_mongodb_atlas_connection_string_here
```

### Start the Application

In both the client and server directories, run:

```bash
npm start
```

## Usage

- Access the web application in your browser at `http://localhost:3000`.
- Server host is at `http://localhost:3001`
- Browse products, add them to your cart, and proceed to checkout.
- Fill out your personal information to complete the order.
- View order history on the Orders page.

## Features

- Product catalog with detailed product information.
- Shopping cart to add and remove items.
- Order history and listing of all orders.
- Responsive design for a seamless user experience.
