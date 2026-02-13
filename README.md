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

---

## 💡 Some Glimpses Of SafeTravel
## Tourist Side
<img width="1011" height="880" alt="1" src="https://github.com/user-attachments/assets/151d8b38-779a-4b69-b94e-f3203df44285" />

<img width="886" height="792" alt="8" src="https://github.com/user-attachments/assets/97412d8b-e899-4ac2-8f35-c8d7eb0f7535" />

<img width="644" height="266" alt="4" src="https://github.com/user-attachments/assets/3e2a3fc0-d42f-4e98-9341-63f7f86ed3f0" />

<img width="634" height="591" alt="5" src="https://github.com/user-attachments/assets/88662813-aabd-4a21-9c7f-49517d137874" />

<img width="846" height="891" alt="6" src="https://github.com/user-attachments/assets/edb68cc6-1ce1-4bf1-a94e-a0934e5898ef" />

<img width="866" height="742" alt="7" src="https://github.com/user-attachments/assets/9db8fb9a-2c79-4684-b6d7-6abf781d7dc0" />



## 💡 Admin Side

<img width="1899" height="908" alt="9" src="https://github.com/user-attachments/assets/2a58ddb9-af07-4651-bcfa-8a69262a510a" />

<img width="1872" height="855" alt="10" src="https://github.com/user-attachments/assets/5c63bd7a-6d60-46a6-a9c9-15784c142399" />

<img width="1919" height="290" alt="11" src="https://github.com/user-attachments/assets/9cc50dc8-5cf1-45c8-a15c-89fb6de97afe" />

