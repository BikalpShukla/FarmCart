# FarmCart

FarmCart is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application that bridges the gap between farmers and buyers. It enables farmers to list, manage, and sell agricultural products online — all through a secure, easy-to-use platform.

-------------------
# Problem Statement:
  
-  Indian farmers face multiple challenges that limit growth and profitability:

- Limited Market Access and Buyer Reach

- Unfair Pricing due to middlemen layers

- Lack of Transparency in pricing and demand

- High Costs from transport and broker fees

- Sustainability & Growth Barriers caused by income instability and market dependence
  
  -------------------------------------------------------------------------------------------------- 
# Problem Solution:
 
We propose a direct, transparent platform that connects farmers with buyers, eliminating intermediaries and reducing access costs.

Key Benefits:
- Reduced Costs: No brokers or unnecessary transport fees

- Fair Pricing: Farmers set prices, ensuring better profits

- Empowerment: Builds direct relationships with industry buyers

- Sustainability: Supports long-term agricultural viability and community upliftment
---------------------------------------------------------------------
# Technologies Used
------------
React: Frontend library for building the user interface.

MongoDB: Database for storing user and product information.

Express.js: Backend framework for building the server and API.

Node.js: Runtime environment for server-side JavaScript execution.

-----------------------------------------------
## Features
-------------
- 🔐 User Authentication**: Secure user login and registration system with JWT-based authentication.
- 🛠️ CRUD Operations**: Users can create, read, update, and delete products or services.
- 📱 Responsive Design**: Fully responsive design for seamless user experience on desktop and mobile devices.
- 📦 Product Management**: Farmers can list products, manage inventory, and track orders.
- 📊 Admin Dashboard**: Manage users, products, and orders efficiently.
- 📦 Order Tracking**: Real-time order status updates for buyers and sellers.
- 📧 Email Notifications**: Integrated email alerts for important updates using Mailtrap.
- 💳 Secure Payment Gateway**: Integrate popular payment gateways for safe transactions (future scope).
--------------------
📁 Folder Structure

```
FarmCart/
├── frontend/        # React Frontend
│   ├── src/         # Source files
│   ├── public/      # Static assets
│   └── package.json # Frontend dependencies
├── backend/         # Node.js Backend
│   ├── models/      # Mongoose schemas
│   ├── routes/      # Express routes
│   ├── controllers/ # Request handlers
│   ├── config/      # DB and server config
│   └── package.json # Backend dependencies
└── README.md        # Project documentation

```
----------------------
## Prerequisites
Ensure you have the following installed on your system:
- **Node.js** (v16.x or later)
- **npm** or **yarn**
- **MongoDB** (running locally or using a cloud-based service like MongoDB Atlas)
- **Git**
-----------------------------------------------
## Getting Started
### 1. Fork and Star the Repository
- Click on the **Fork** button at the top-right corner of this repository to create your own copy.
- If you find this project useful, don’t forget to give it a **Star**!

### 2. Clone the Repository
```bash
git clone <forked repository URL>
cd FarmCart
```

### 3. Install Dependencies

#### Backend
Navigate to the backend directory and install dependencies:
```bash
cd backend
npm install
```

#### Frontend
Navigate to the frontend directory and install dependencies:
```bash
cd frontend
npm install
```

### 4. Environment Variables
Create a `.env` file in the root of your backend directory and add the following:
```
MONGO_URI=Your_MongoDB_URI
PORT=5000
JWT_SECRET=Your_Secret_Key
MAILTRAP_TOKEN=Your_Mailtrap_Token
CLIENT_URL=http://localhost:5173/
EMAIL_PASS=Your_16_Digit_Password
```

### 5. Start the Development Server

#### Frontend
To start the React application:
```bash
npm run dev
```

#### Backend
To start the Node.js server:
```bash
node server.js
```

---

# Contributing

We welcome contributions from everyone! Here’s how you can help:

2. **Suggest Features**: Have a feature in mind? Feel free to suggest it.
3. **Submit Pull Requests**: If you’d like to contribute code, follow these steps:
    - Fork the repository.
    - Create a feature branch: `git checkout -b feature/your-feature-name`.
    - Commit your changes: `git commit -m 'Add your feature'`.
    - Push the branch: `git push origin feature/your-feature-name`.
    - Open a pull request.
4. **Improve Documentation**: Help us keep the documentation up to date.

---

## Future Enhancements

- **Payment Gateway Integration**: Add support for online transactions.
- **Advanced Analytics**: Provide insights for farmers to improve sales.
- **Localization**: Support multiple languages for a global reach.
- **Mobile App**: Develop a dedicated mobile application for iOS and Android.

---
# Group Members
-----------------------------

Bikalp Shukla (Team Leader)

Aditya kumar

Divyanshi Verma

Bhumika Sonare

Anamika Ankolnerkar

----------------------------

Thank you😊

