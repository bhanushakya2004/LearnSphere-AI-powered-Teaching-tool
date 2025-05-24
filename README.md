
# LearnSphere 🎓🤖

**LearnSphere** is an AI-powered full-stack teaching assistant platform built with the **MERN stack**, designed to enhance teaching productivity through automation, scheduling, and performance analytics.

---

## 🚀 Features

- ✍️ **Assignment Generator** – Create assignments automatically with AI assistance.
- 📅 **Meet Scheduler** – Schedule Google Meet sessions with Calendar integration.
- 📧 **Assignment Checker** – Auto-evaluate and provide insights.
- 🧪 **Test Scheduler** – Plan and notify upcoming tests seamlessly.
- 📊 **Performance Analysis** – Track student progress using visual analytics.
- 🔐 **Google OAuth 2.0** – Secure login with Google accounts.

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS / Styled Components (optional)
- Axios

### Backend
- Node.js + Express.js
- MongoDB + Mongoose + Firebase
- Google APIs (Calendar, Gmail, Meet, Sheets)
- Google OAuth 2.0
- GCP Cloud Run (for backend deployment)
- JWT (if additional auth used)

---

## ☁️ Google Cloud Services Used

- 🔑 **OAuth 2.0** – Secure access to Google user data.
- 📅 **Google Calendar API** – For scheduling classes, meetings, and tests.
- 📬 **Gmail API** – For sending assignment/test notifications.
- 📊 **Google Sheets API** – For storing and analyzing student performance.
- 📹 **Google Meet API** – For live session integration.
- 🚀 **GCP Cloud Run** – For scalable backend deployment.

---


## 📦 .env Configuration

```env
PORT=5000
MONGO_URI=your_mongo_uri
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GOOGLE_REDIRECT_URI=your_google_oauth_redirect
JWT_SECRET=your_jwt_secret
FRONTEND_URL=http://localhost:3000

```


🌍 Live Demo
https://learn-sphere-ai-powered-educational-platform.vercel.app/ 
Backend deployed on GCP Cloud Run

🧑‍💻 Author
Built with ❤️ by Bhanu Shakya

📄 License
MIT License
