# 🚀 FocusRoom – Organizational Pomodoro Productivity Tracker

## 📌 Overview

**FocusRoom** is a web-based productivity platform that helps organizations and teams stay focused, manage tasks, and track productivity using the **Pomodoro technique**.

Unlike regular Pomodoro apps designed for individuals, FocusRoom focuses on **collaboration**:

- Create or join organization rooms with a code
- Track live focus sessions of all team members
- Manage tasks using a Kanban-style board
- View analytics and reports for individuals and the whole team

---

## ✨ Features

### ✅ Core Features

- 🎯 Pomodoro Timer (25 min work + 5 min break)
- 👥 Team/Organization Rooms (join with a code)
- 📊 Live Status Cards – see who's working, on break, or idle
- 📑 Task Management – assign tasks and track progress
- 📈 Analytics Dashboard – track sessions and completed tasks
- 🔐 Google Authentication (Firebase)

---

## 🖼️ Screens (Figma Design)

👉 [View Figma Design](https://www.figma.com/design/MJb0UIhjZQbtycli5CRhXf/Untitled?node-id=0-1&t=cAWPsfGdGPwP1uAm-1)

---

## 🌍 Deployment

- **Frontend:** [Live Link](https://focus-room-zeta.vercel.app)

---

## 🛠️ Tech Stack

- **Frontend:** React.js + TailwindCSS
- **Backend:** Firebase
- **Database:** Firestore
- **Charts:** Recharts
- **Deployment:** Vercel
- **Design:** Figma

---

## 📂 Project Structure

```
/FocusRoom
├── /public          # Static assets
├── /src
│   ├── /components   # Reusable UI components
│   ├── /pages        # Landing, Dashboard, Tasks, Analytics, etc.
│   ├── /utils        # Helper functions
│   └── App.js        # Main app entry
├── package.json
└── README.md
```

---

## 🧑‍💻 How to Run Locally

1. **Clone the repo:**

   ```bash
   git clone https://github.com/kalviumcommunity/FocusRoom.git
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run development server:**

   ```bash
   npm run dev
   ```

4. **Open** `http://localhost:5173` in your browser.

---

## 📊 Future Improvements

- 📌 Mobile App (Flutter/React Native)
- ⏰ Customizable Pomodoro durations
- 🏆 Gamified achievements and streaks
- 🤝 Integrations with Slack, Google Calendar, Notion
