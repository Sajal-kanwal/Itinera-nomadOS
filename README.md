# 🌍 Itinera-nomadOS

**AI-powered travel agency platform** with a sleek public-facing site and a powerful admin dashboard. Easily generate personalized trip itineraries, manage bookings, track user growth, and visualize analytics — all in one unified web application.

---

## ✨ Features

- 🤖 **AI Trip Itinerary Generator**  
  Generate smart, personalized trip plans based on country, budget, interests, group size, and travel style.

- 🧳 **Trip Booking System**  
  Seamless public booking interface with full trip previews.

- 📊 **Admin Dashboard**  
  Manage users and trips with advanced analytics and growth metrics.

- 📈 **Interactive Charts**  
  Visualize key metrics using dynamic charts and stats tables.

- 🔐 **Secure Auth & Data Management**  
  Appwrite-backed user authentication and real-time database integration.

- ⚡ **Responsive UI & Smooth UX**  
  Mobile-first design with modern components, transitions, and state management.

---

## 🛠️ Tech Stack

| Frontend            | Backend / Services   | UI & Libraries         |
|---------------------|----------------------|-------------------------|
| React 19            | Appwrite             | Syncfusion Components  |
| React Router v7     | —                    | Tailwind CSS           |
| Vite                |                      |                         |

---

## 📁 Folder Structure (Simplified)

```text
Itinera-nomadOS/
├── public/                  # Static assets (favicon, index.html, etc.)
├── src/
│   ├── components/          # Reusable UI components (Header, Button, etc.)
│   ├── pages/               # Public and admin-facing pages
│   ├── services/            # Appwrite and other API integrations
│   ├── utils/               # Utility functions and helpers
│   ├── hooks/               # Custom React hooks
│   └── App.jsx              # Root component
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Itinera-nomadOS.git
cd Itinera-nomadOS
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Set Up Environment
Create a .env file based on .env.example:

```env
VITE_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DB_ID=your_db_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
```

### 4. Start the Dev Server
```bash
npm run dev
```

## 📊 Screenshots
Coming soon...
Admin dashboard, itinerary generator, and trip overview UI.

## 📌 Roadmap
 Itinerary generation via AI prompt templates

 Basic booking interface

 Admin dashboard + charts

 Stripe/UPI integration

 Realtime chat with travel assistant

 Mobile app with PWA support

 ## 🤝 Contributing
PRs are welcome! Please open an issue first for major changes.
For local dev instructions, see CONTRIBUTING.md (optional).
