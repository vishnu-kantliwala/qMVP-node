# 🚖 Cab Booking System

A **Node.js-based** cab booking system using **Express**, **TypeScript**, **MongoDB**, and **Mongoose** with **role-based authentication**.

## 🌟 Features
- 🔐 **User Authentication** (JWT & bcrypt)
- 👥 **Role-Based Access Control** (Admin, Driver, Passenger)
- 🚕 **Cab Booking & Ride Management**
- 🗄 **MongoDB with Mongoose ORM**
- 📡 **RESTful API with Express**
- ✅ **Input Validation** with Express Validator

---

## 📥 Installation

### ⚙️ Prerequisites
- 🟢 **Node.js** (>=16.0.0)
- 🍃 **MongoDB** (Local or Cloud - e.g., MongoDB Atlas)

### 🔧 Steps
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-repo/cab-booking-system.git
   cd cab-booking-system
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Set up environment variables:**
   - Create a `.env` file in the root directory and add the following:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     ```
4. **Start the development server:**
   ```sh
   npm run dev
   ```
5. **Build the project:**
   ```sh
   npm run build
   ```
6. **Run in production:**
   ```sh
   npm start
   ```

---

## 📌 API Endpoints

### 🔑 Authentication
- `POST /api/auth/register` - ✍️ Register a new user
- `POST /api/auth/login` - 🔑 User login

### 👤 Users
- `GET /api/users` - 📃 Get all users (**Admin only**)
- `GET /api/users/:id` - 🔍 Get user by ID

### 🚕 Rides
- `POST /api/rides` - 🏁 Book a ride
- `GET /api/rides` - 📜 Get ride history

---

## 🤝 Contributing
🚀 Feel free to **fork** this repository, create a new branch, and submit **pull requests**!

---

## 📜 License
📝 **MIT License** - You are free to modify and distribute this software under the **MIT License**.

---

### ❤️ Support
⭐ If you like this project, **give it a star** on GitHub!
