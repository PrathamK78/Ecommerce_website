# Forever E-Commerce Website

Forever is a full-stack e-commerce website built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides users with a seamless shopping experience and includes powerful features such as product management, authentication, and a responsive UI designed with Tailwind CSS. The state is managed using Redux for efficient data flow and user experience.

---

## Features

- **Responsive Design**: Fully mobile-friendly UI with Tailwind CSS.
- **Product Management**: Add, edit, and delete products.
- **User Authentication**: Secure login and signup with JWT.
- **Shopping Cart**: Add products to the cart and proceed to checkout.
- **Redux State Management**: Efficient state handling for cart and user data.
- **Backend API**: Built with Node.js, Express.js, and MongoDB.

---

## Tech Stack

### Frontend:
- **React.js**
- **Tailwind CSS**
- **Redux**

### Backend:
- **Node.js**
- **Express.js**
- **MongoDB**

---

## Installation

Follow these steps to set up the project on your local machine.

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v14+)
- **MongoDB** (running locally or a cloud instance)
- **Git**

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/forever-ecommerce.git
cd forever-ecommerce
```

### 2. Install Dependencies

#### For the Backend
```bash
cd backend
npm install
```

#### For the Frontend
```bash
cd ../frontend
npm install
```

### 3. Set Environment Variables
Create a `.env` file in the `backend` folder and add the following:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4. Run the Application

#### Start the Backend Server
```bash
cd backend
npm run dev
```

#### Start the Frontend Development Server
```bash
cd ../frontend
npm start
```

### 5. Access the Application
Open your browser and navigate to:
```
http://localhost:3000
```

---

## Folder Structure
```
forever-ecommerce/
├── backend/             # Backend API
│   ├── controllers/     # API controllers
│   ├── models/          # MongoDB models
│   ├── routes/          # API routes
│   ├── server.js        # Entry point for the backend
│   └── .env             # Environment variables
├── frontend/            # React frontend
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── pages/       # Application pages
│   │   ├── redux/       # Redux slices and store
│   │   └── App.js       # Main React component
├── README.md            # Documentation
└── package.json         # Project metadata
```

---

## Scripts

### Backend
- `npm run dev`: Starts the backend server in development mode.
- `npm start`: Starts the backend server in production mode.

### Frontend
- `npm start`: Starts the React development server.
- `npm run build`: Builds the React app for production.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
For any questions or suggestions, feel free to reach out:
- **Email**: dharmender7077@gmail.com
- **GitHub**: [yourusername](https://github.com/techiedharam)
