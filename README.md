# Real-time Chat Application

A real-time chat application built with the MERN stack, featuring instant messaging, authentication, and a modern UI.

## 🚀 Features
- 🔐 **Authentication & Authorization** – Secure login & JWT-based authentication.
- 💬 **Real-time Messaging** – Powered by Socket.io for instant communication.
- 🟢 **Online User Status** – Display active users dynamically.
- 📌 **Global State Management** – Managed efficiently with Zustand.
- 🎨 **Modern UI** – Built with TailwindCSS & DaisyUI.
- 🛠 **Error Handling** – Robust error management on both client & server.
- 🚀 **Free Deployment** – Hosted with modern cloud solutions.

## 🛠 Tech Stack
- **Frontend:** React.js, TailwindCSS, DaisyUI
- **Backend:** Node.js, Express.js, MongoDB
- **WebSockets:** Socket.io
- **State Management:** Zustand
- **Authentication:** JWT
- **Deployment:** Free cloud hosting

## 📂 Project Structure
```
📦 realtime-chat-app
├── 📂 client        # React Frontend
│   ├── 📂 src
│   │   ├── 📂 components
│   │   ├── 📂 pages
│   │   ├── 📂 store (Zustand)
│   │   ├── 📄 App.js
│   │   ├── 📄 index.js
├── 📂 server        # Node.js Backend
│   ├── 📂 config    # Database & JWT setup
│   ├── 📂 controllers
│   ├── 📂 models
│   ├── 📂 routes
│   ├── 📂 middleware
│   ├── 📄 server.js
```

## ⚙️ Installation & Setup
### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/realtime-chat-app.git
cd realtime-chat-app
```
### 2️⃣ Install dependencies
#### For backend
```sh
cd server
npm install
```
#### For frontend
```sh
cd client
npm install
```

### 3️⃣ Set up environment variables
Create a `.env` file in the **server** folder with:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
SOCKET_PORT=your_socket_port
```

### 4️⃣ Run the application
#### Start the backend
```sh
cd server
npm start
```
#### Start the frontend
```sh
cd client
npm start
```

## 📌 Deployment
- **Frontend:** Vercel / Netlify
- **Backend:** Render / Railway / Heroku
- **Database:** MongoDB Atlas

## 📜 License
This project is licensed under the **MIT License**.

---

Happy coding! 🚀

