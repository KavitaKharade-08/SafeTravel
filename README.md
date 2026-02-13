# 🛡️ SAFETravel – AI-Powered Tourist Safety System

SAFETravel is an intelligent tourist safety platform built using **Next.js (React + TypeScript) and Firebase**.
It provides real-time risk detection, smart emergency alerts, AI-based monitoring, and centralized admin control to enhance tourist safety.

---

## 🚀 Tech Stack

* **Framework:** Next.js 16 (React + TypeScript)
* **Styling:** Tailwind CSS
* **Database:** Firebase Firestore
* **Authentication:** Firebase Auth
* **Real-time Updates:** Firestore Snapshot Listeners
* **Deployment Ready:** Vercel / Firebase Hosting

---

## 🧠 Core Features

### 👤 User Side

* User Registration & Login
* Protected Routes
* AI Risk Zone Detection (Green / Yellow / Red)
* Safe Route Recommendation
* Real-Time Heatmap
* Smart Incident Reporting (with image & severity)
* Multi-Mode SOS (Button / Shake / Voice)
* Live Location Sharing
* Offline Emergency SMS Support
* Agentic AI Safety Guardian
* Multi-language Support
* AI Chat Safety Assistant

---

### 🛠️ Admin Side

* Real-Time Incident Dashboard
* Live SOS Monitoring
* Severity Tracking
* Risk Heatmap Visualization
* Incident Status Management
* Nearest Hospital Coordination
* Response Time Tracking
* Data Analytics for Safety Planning

---

## ⚙️ Installation & Setup

### 1️⃣ Install Dependencies

```bash
npm install --legacy-peer-deps
```

> `--legacy-peer-deps` resolves peer dependency conflicts.

---

### 2️⃣ Configure Firebase

Create a file in the root directory:

```
.env.local
```

Add your Firebase configuration:

```env
NEXT_PUBLIC_FIREBASE_API_KEY=YOUR_API_KEY
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=YOUR_PROJECT.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=YOUR_PROJECT.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=YOUR_SENDER_ID
NEXT_PUBLIC_FIREBASE_APP_ID=YOUR_APP_ID
```

⚠️ Do not use quotes around values.
⚠️ Restart the development server after adding environment variables.

---

### 3️⃣ Run Development Server

```bash
npm run dev
```

Open in your browser:

```
http://localhost:3000
```

---

## 🔥 Firestore Index Setup (Important)

If you encounter:

```
FirebaseError: failed-precondition: The query requires an index
```

Create a composite index in Firebase Console:

Example configuration:

| Collection ID | Field 1            | Field 2                | Query Scope |
| ------------- | ------------------ | ---------------------- | ----------- |
| incidents     | status (Ascending) | timestamp (Descending) | Collection  |

After the index builds, refresh the application.

---

## 🧪 Testing Checklist

### User Side

* [ ] Register new user
* [ ] Login / Logout
* [ ] Trigger SOS
* [ ] Submit Incident Report
* [ ] View Risk Zones
* [ ] Check Safe Route Feature

### Admin Side

* [ ] View live incidents
* [ ] Change incident status
* [ ] Monitor severity
* [ ] View heatmap updates
* [ ] Track response time

---

## 🔐 Security

* Firebase Authentication enabled
* Firestore security rules applied
* Environment variables secured in `.env.local`
* Protected admin routes

---

## 🌍 Deployment

### Deploy to Vercel

```bash
vercel
```

### Deploy to Firebase Hosting

```bash
firebase deploy
```

---

## 💡 Innovation Highlights

* AI-based predictive risk scoring
* Agentic autonomous safety monitoring
* Multi-mode emergency trigger system
* Real-time heatmap intelligence
* Centralized command dashboard

reademe file
