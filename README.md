# 💬 TalkTuMe - Real-Time Fullstack Chat Application

![TalkTuMe Demo](./frontend/public/screenshot-for-readme.png)

A modern, high-performance real-time chat application built with the MERN stack (MongoDB, Express, React, Node.js) and Socket.io. TalkTuMe provides a seamless messaging experience with real-time updates, user presence tracking, and a beautiful UI.

## 🚀 Features

- **Real-time Messaging**: Instant message delivery powered by Socket.io.
- **Online/Offline Status**: Track who's currently active in the app.
- **Authentication & Authorization**: Secure user login and signup using JWT (JSON Web Tokens).
- **Profile Customization**: Users can upload and update their profile pictures via Cloudinary.
- **Responsive Design**: Fully responsive UI built with Tailwind CSS and DaisyUI, looking great on all devices.
- **Global State Management**: Efficient state handling with Zustand.
- **Secure Architecture**: Server-side error handling and protected routes.

---

## 🛠️ Tech Stack

### Frontend
- **React**: Modern UI development.
- **Zustand**: Lightweight and scalable state management.
- **Tailwind CSS & DaisyUI**: For rapid and beautiful styling.
- **Socket.io-client**: Real-time communication on the client side.
- **React Router Dom**: Client-side routing.
- **React Hot Toast**: Beautiful notification system.
- **Lucide React**: Clean and consistent iconography.

### Backend
- **Node.js & Express**: High-performance backend environment.
- **MongoDB & Mongoose**: Flexible NoSQL database for message and user storage.
- **Socket.io**: Real-time bidirectional event-based communication.
- **Cloudinary**: Cloud-based image management for profile avatars.
- **Web Tokens (JWT)**: Secure authentication mechanism.
- **Bcryptjs**: Password hashing for security.

---

## 📦 Getting Started

### Prerequisites

- Node.js installed on your machine.
- A MongoDB database (Atlas or local).
- A Cloudinary account for file uploads.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kaushik2709/FullStack_ChatApp.git
   cd FullStack_ChatApp
   ```

2. **Install Dependencies:**
   
   Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```

   Install frontend dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

3. **Environment Variables:**

   Create a `.env` file in the `backend` directory and add the following:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   PORT=5001
   JWT_SECRET=your_jwt_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   NODE_ENV=development
   ```

### Running the Application

1. **Start the Backend Server:**
   ```bash
   cd backend
   npm run dev
   ```

2. **Start the Frontend Application:**
   ```bash
   cd frontend
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:5173`.

---

## 📂 Project Structure

```text
├── backend/                # Express server and socket logic
│   ├── src/
│   │   ├── controllers/    # API request handlers
│   │   ├── lib/            # Shared utilities (db, socket, tokens)
│   │   ├── models/         # Database schemas
│   │   └── routes/         # API endpoints
├── frontend/               # React application
│   ├── src/
│   │   ├── components/     # Reusable UI parts
│   │   ├── lib/            # Axios instance and utils
│   │   ├── pages/          # Main application screens
│   │   └── store/          # Zustand state management
└── README.md
```

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

Developed with ❤️ by [Kaushik](https://github.com/Kaushik2709)
