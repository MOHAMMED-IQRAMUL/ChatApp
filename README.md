# Full Stack Realtime Chat App

Welcome to the **Full Stack Realtime Chat App**! This application is designed for seamless real-time communication with modern features and a clean, responsive UI.

---

## Features

- **Real-Time Messaging**: Powered by Socket.io for instant communication.
- **Authentication & Authorization**: Secure login/signup using JWT.
- **Modern Tech Stack**: Built with MERN (MongoDB, Express, React, Node.js) and TailwindCSS.
- **Global State Management**: Using Zustand for effortless state handling.
- **File Uploads**: Integrated with Cloudinary for image storage.
- **User Status**: Real-time online/offline tracking.
- **Responsive Design**: Mobile-first with TailwindCSS and DaisyUI components.

---

## Getting Started

### Prerequisites

- **Node.js** (>=14.x)
- **npm** or **yarn**
- **MongoDB** (local or cloud instance)

---

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/chat-app.git
   cd chat-app
   ```

2. Install dependencies for both backend and frontend:
   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

3. Configure your `.env` file in the `backend/` directory:
   ```env
   MONGODB_URI=your_mongodb_uri
   PORT=5001
   JWT_SECRET=your_jwt_secret

   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret

   NODE_ENV=development
   ```

4. Start the backend server:
   ```bash
   cd backend && npm start
   ```

5. Start the frontend development server:
   ```bash
   cd frontend && npm run dev
   ```

6. Access the app 

---


## Scripts

### Backend
- **Start development server:**
  ```bash
  npm start
  ```
- **Run seed scripts:**
  ```bash
  node src/seeds/user.seed.js
  ```

### Frontend
- **Start development server:**
  ```bash
  npm run dev
  ```
- **Build for production:**
  ```bash
  npm run build
  ```

---

## License

This project is licensed under the [MIT License](./LICENSE).

---

Happy coding! 🚀

