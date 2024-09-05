# 📚 Book Store - MERN Stack Project

A full-stack Book Store web application built using the MERN stack (MongoDB, Express, React, Node.js) and styled with Tailwind CSS. The app allows users to browse, purchase books, and manage their accounts. Admin users can manage books and orders.

## 🚀 Features

- User authentication (Register, Login, Logout)
- Browse and search for books
- View detailed book information
- Add books to cart and proceed to checkout
- Admin panel for managing books and orders
- Responsive UI with Tailwind CSS
- Secure JWT-based authentication

## 🛠 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **Version Control**: Git
- **Deployment**: (Optional: Mention your deployment platform like Heroku, Vercel, etc.)

## 📂 Folder Structure

```bash
book-store/
├── client/                  # Frontend (React + Tailwind CSS)
│   ├── public/              # Static files
│   ├── src/                 # React components, hooks, services
│   └── tailwind.config.js   # Tailwind CSS configuration
│
├── server/                  # Backend (Node.js + Express)
│   ├── controllers/         # Logic for handling requests
│   ├── models/              # Mongoose models
│   ├── routes/              # API endpoints
│   ├── middleware/          # Authentication and authorization
│   ├── config/              # Environment variables and configuration
│   └── server.js            # Entry point of the backend
│
└── README.md                # Project documentation
```
````

## 🔧 Installation

To run this project locally, follow these steps:

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (Installed locally or use MongoDB Atlas)
- [Git](https://git-scm.com/)

### 1. Clone the repository

```bash
git clone https://github.com/your-username/book-store.git
cd book-store
```

### 2. Install dependencies

#### Backend (Server)

```bash
cd server
npm install
```

#### Frontend (Client)

```bash
cd ../client
npm install
```

### 3. Set up environment variables

Create a `.env` file in the `server` directory and add the following variables:

```bash
MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret-key
```

### 4. Run the application

#### Backend

```bash
cd server
npm start
```

#### Frontend

```bash
cd client
npm start
```

Now, open your browser and go to `http://localhost:3000`.

## ⚙️ Usage

### Admin Access

To access the admin dashboard, sign up as a user, and manually update your role to `admin` in the MongoDB database.

- Admin functionalities include managing books and viewing orders.

## 💻 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Make your changes and commit: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## ✉️ Contact

For any questions or issues, please contact:

- **Your Name**: [your.email@example.com](mailto:your.email@example.com)
- GitHub: [https://github.com/your-username](https://github.com/your-username)

```

This template provides a clean, structured, and detailed README file in a GitHub-friendly format. Be sure to replace placeholder text (like "your-username" and "your.email@example.com") with your actual information.
```
