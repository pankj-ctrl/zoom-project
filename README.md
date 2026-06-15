```md
# LiveTalk - Video Conferencing App 📹

LiveTalk is a full-stack video calling application built using the MERN stack and WebRTC. It allows users to create, join, and manage video meetings seamlessly with real-time communication.

## 🚀 Features

* **User Authentication:** Secure login and registration for users.
* **Instant Meetings:** Start a video call instantly and share the meeting code with others.
* **Join Meetings:** Join an ongoing meeting using a unique meeting code.
* **Real-time Communication:** High-quality video and audio streaming using WebRTC and Socket.io.
* **Meeting History:** Keep track of your past meetings and call logs.
* **Responsive UI:** Clean and simple user interface built with React and Material-UI.

## 💻 Tech Stack

**Frontend:**
* React.js
* Material-UI (MUI)
* CSS Modules (for styling)
* Socket.io-client

**Backend:**
* Node.js
* Express.js
* MongoDB (Mongoose for data modeling)
* Socket.io (for real-time signaling)

## 🛠️ Installation & Setup

Follow these steps to run the project on your local machine.

### Prerequisites
* Node.js installed on your computer
* MongoDB installed or a MongoDB Atlas URI

### 1. Clone the Repository
```bash
git clone <your-github-repo-url>
cd zoom-project

```

### 2. Backend Setup

```bash
cd backend
npm install

```

* Create a `.env` file in the `backend` folder and add your environment variables:
```env
MONGO_URL=your_mongodb_connection_string

```


* Start the backend server:

```bash
npm start

```

### 3. Frontend Setup

```bash
cd frontend
npm install

```

* Start the React development server:

```bash
npm start

```

## 📂 Folder Structure

* `backend/` - Contains all server-side code (Models, Controllers, Routes, Socket Manager).
* `frontend/` - Contains all client-side code (React Pages, Components, Contexts).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📝 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

