# 💸 FinMate

**FinMate** is a MERN Stack project built in 48 hours during **HackEd IT**, a hackathon organized in collaboration with **GrowthEd**.  
The project simplifies financial decision-making by offering intuitive and smart budget tracking and poll-based prioritization.

> ⚠ *Note:* For the best viewing experience, please avoid using *dark mode* while browsing this README.

## 🚀 Deployed Link

🔗 [Live Demo](https://fin-mate-smart-student-expense-tracker.vercel.app/login)  
📽️ [Demo Video](https://youtube.com/your-demo-video-link)

---

## 👥 Contributors

- **Akash Pandey** — Frontend Developer  
  - Built the React-based frontend  
  - Implemented UI/UX and handled React Router for navigation  
  - Designed and structured the entire frontend application  
  - Integrated API endpoints with user interface components

- **Arpit Makkar** — Backend Developer  
  - Set up the Express.js backend
  - Managed MongoDB integration and API endpoints
  - Deployed the backend on Render
  - Also deployed the frontend on Vercel

---

## 🛠️ Tech Stack

- **Frontend**: React, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Auth**: JWT
- **Deployment**: Vercel (Frontend), Render (Backend)

---

## 🧩 Features

- 📊 Real-time financial analytics
- 🔐 JWT-secured user authentication
- 🌐 Fully responsive UI
- 🔄 RESTful API architecture

---

## 📦 Getting Started – Local Setup

To run the project locally, follow the steps below:

---

### 🔧 Backend Setup (Express.js)

1. Navigate to the `backend` folder:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up MongoDB:
   - Visit [MongoDB](https://www.mongodb.com/) and log in or create an account
   - Create a new project and cluster (free tier)
   - Add a user and allow IP access
   - Copy the connection string for your project

4. Update your `.env` file:
   ```env
   MONGODB_URI=your_connection_string_here
   JWT_SECRET=your_generated_jwt_secret
   ```

   To generate a secret:
   ```bash
   node -e "console.log(require('crypto').randomBytes(64).toString('hex'))"
   ```

5. Start the backend server:
   ```bash
   npm run dev
   ```

---

### 💻 Frontend Setup (React)

1. Navigate to the frontend folder:
   ```bash
   cd frontend/polling-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm run dev
   ```

The app will open in your browser at [http://localhost:5173](http://localhost:5173) by default.

---

## 📁 Project Structure

```bash
finmate/
├── backend/              # Express backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── .env
├── frontend/
│   └── polling-app/      # React frontend
│       ├── components/
│       ├── pages/
│       └── App.jsx
└── README.md
```

---

## 📌 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Special thanks to the organizers of **HackEd IT** and **GrowthEd** for facilitating such an exciting and innovative hackathon experience.

---
