# 🚀 AI Form Builder (Typeform Clone)

A full-stack MERN application to create dynamic, AI-powered forms similar to Typeform.
Users can generate forms using prompts, share them, and view responses in a dashboard.

---

## ✨ Features

* 🧠 AI-based form generation (via Groq API)
* 📝 Multi-step interactive form experience
* 🔗 Shareable public form links
* 📊 Response dashboard with analytics
* 🔐 User authentication (login/register)
* 📱 Fully responsive UI (mobile-friendly)
* ⚡ Works even without AI key (fallback schema generation)

---

## 🛠 Tech Stack

**Frontend**

* React
* Vite
* CSS / Tailwind (if used)

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB Atlas

**AI Integration**

* Groq API (optional)

---

## 📁 Project Structure

```
client/   → React frontend
server/   → Express backend
```

---

## ⚙️ Setup & Run Locally

### 1. Clone the repository

```
git clone https://github.com/7starprajwal/formforge-ai.git
cd formforge-ai
```

---

### 2. Install dependencies

```
npm install
cd client && npm install
cd ../server && npm install
```

---

### 3. Configure environment variables

Create a file:

```
server/.env
```

Add:

```
PORT=5000
CLIENT_URL=http://localhost:5173
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
GROQ_API_KEY=your_api_key
```

---

### 4. Run the project

Start backend:

```
cd server
npm run dev
```

Start frontend:

```
cd client
npm run dev
```

---

## 🌐 Local URLs

* Frontend → http://localhost:5173
* Backend → http://localhost:5000

---

## 🚀 Future Improvements

* Drag-and-drop form builder
* Pre-built templates
* Email notifications
* Advanced analytics dashboard

---

## 👨‍💻 Author

**Prajwal**
GitHub: https://github.com/7starprajwal

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
