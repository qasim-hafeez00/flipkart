# Flipkart Clone (ECommerce-Website)

A full-featured Flipkart-inspired e-commerce web application built with the MERN stack (MongoDB, Express, React, Node.js). It supports user authentication, product browsing, cart management, and payment integration via Paytm.

---

## Table of Contents

1. [Demo](#demo)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Getting Started](#getting-started)

   * [Prerequisites](#prerequisites)
   * [Installation](#installation)
   * [Environment Variables](#environment-variables)
   * [Running the App](#running-the-app)
5. [Project Structure](#project-structure)
6. [Available Scripts](#available-scripts)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

---

---

## Features

* **User Authentication** (Signup / Login)
* **Product Catalog**: Browse products by categories
* **Search**: Real-time search functionality
* **Shopping Cart**: Add, update quantity, and remove items
* **Checkout & Payment**: Integrated Paytm payment gateway
* **Order History**: View past orders
* **Responsive Design**: Mobile-friendly UI

---

## Tech Stack

* **Frontend**: React, Redux, Context API, Tailwind CSS
* **Backend**: Node.js, Express.js
* **Database**: MongoDB (Mongoose ODM)
* **Payment**: Paytm integration via PaytmChecksum
* **Authentication**: JWT-based auth

---

## Getting Started

### Prerequisites

* Node.js (v14+)
* npm or yarn
* MongoDB (local or Atlas)

### Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/qasim-hafeez00/flipkart.git
   ```
2. Install server dependencies:

   ```bash
   cd flipkart/ECommerce-Website/server
   npm install
   ```
3. Install client dependencies:

   ```bash
   cd ../client
   npm install
   ```

### Environment Variables

Create a `.env` file in `server` directory with the following keys:

```dotenv
MONGODB_URI=<your_mongo_connection_string>
JWT_SECRET=<your_jwt_secret>
PAYTM_MERCHANT_ID=<your_paytm_mid>
PAYTM_MERCHANT_KEY=<your_paytm_key>
PAYTM_WEBSITE=WEBSTAGING
PAYTM_CHANNEL_ID=WEB
PAYTM_INDUSTRY_TYPE_ID=Retail
```

### Running the App

From the root directory (`flipkart`):

```bash
# start server
cd ECommerce-Website/server
npm start

# in a separate terminal, start client
cd ../client
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

---

## Project Structure

```
flipkart/
├── ECommerce-Website/
│   ├── client/          # React frontend
│   └── server/          # Node/Express backend
└── README.md            # Project overview
```

---

## Available Scripts

In the `client` and `server` folders run:

* `npm start` - Starts the development server
* `npm run build` - Builds production-ready assets (frontend)
* `npm test` - Launches test runner (frontend)
* `npm run eject` - Ejects CRA configuration (frontend)

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with improvements.

---

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.

---

## Contact

* GitHub: [qasim-hafeez00](https://github.com/qasim-hafeez00)
* Email: [f223812@cfd.nu.edu.pk](mailto:f223812@cfd.nu.edu.pk)
