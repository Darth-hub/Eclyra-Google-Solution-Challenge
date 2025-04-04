# Eclyra - Google Solution Challenge 2025

Team Eclyra's project repository for the Google Solution Challenge 2025.

## 📚 Contents
- [🔗 Repository Links](#-repository-links)
- [🌍 Overview](#-overview)
- [🛠️ Tech Stack](#%ef%b8%8f-tech-stack)
- [🔑 Key Features](#-key-features)
- [🚀 Getting Started](#-getting-started)
- [⚙️ Configuration](#%ef%b8%8f-configuration)
- [🤝 Contributors](#-contributors)
- [📜 License](#-license)

## 🔗 Repository Links
- **Frontend Repository:** [Eclyra Frontend](https://github.com/simple2226/gsc_frontend)
- **Backend Repository:** [Eclyra Backend](https://github.com/simple2226/gsc_backend)
- **MVP Live Link:** [Eclyra](https://eclyra.netlify.app/)

## 🌍 Overview
Eclyra is revolutionizing waste management by providing a sustainable and profitable platform for individuals and businesses. It bridges the gap between scrap sellers and collectors, ensuring recyclable materials contribute to a circular economy instead of being wasted.

The project is built using:
- **ReactJS** for a dynamic frontend.
- **Firebase** for authentication, real-time updates, and hosting.
- **Tailwind CSS** for styling.
- **Firestore** as the database.
- **Vertex AI & Dialogflow CX** for AI-powered chatbot integration.

---

## 🛠️ Tech Stack
### **Frontend**
- **Vite + React**: Fast and modern frontend framework.
- **Tailwind CSS**: Utility-first CSS for rapid UI development.
- **Mantine UI**: Provides modern, accessible UI components.
- **Firebase Authentication**: Secure and scalable authentication.

### **Backend**
- **Firebase Firestore**: NoSQL cloud database with real-time syncing.
- **Node.js & Express.js**: Lightweight and efficient backend framework.

### **AI & Chatbot**
- **Vertex AI & Dialogflow CX**: AI chatbot for assisting users with scrap pickups, answering queries, and providing recycling insights.

### **APIs**
- **Google Maps API**: Enables accurate scrap pickup locations, route optimization, and real-time navigation.
- **Gemini API**: Enhances user interactions and provides quick responses to users with EclyraSearch.

### **Additional Tools**
- **NPM**: Manages project dependencies.
- **Git & GitHub**: Version control and collaboration.
- **Google Cloud**: Hosting, cloud storage, authentication, and Maps services.

---

## 🔑 Key Features
### **1️⃣ Secure Authentication**
- **User Registration & Login**: Firebase Authentication ensures secure access.
- **Token-Based Authentication**: Enables protected user sessions.

### **2️⃣ Scrap Selling & Pickup**
- **Order Placement**: Users can schedule scrap pickups via chatbot or UI.
- **Real-Time Pricing**: Dynamic scrap pricing based on market rates.
- **Multi-Industry Selling**: Users can sell scrap to multiple industries instead of a single dealer.

### **3️⃣ AI-Powered Chatbot**
- **Order Assistance**: Users can place orders directly via chatbot.
- **Instant Queries**: Answers questions about recycling, pricing, and processes.
- **Multilingual Support**: Handles both **English and Hindi**.

### **4️⃣ Community Engagement**
- **Cleaning Drives**: Encourages community participation in environmental efforts.
- **Reward System**: Users earn points for responsible waste disposal.

### **5️⃣ Scalable & Efficient Architecture**
- **Cloud-Hosted**: Deployed on **Render (backend)** and **Netlify (frontend)**.
- **Optimized Performance**: Uses Firebase Firestore for real-time data and scalable storage.

### **6️⃣ Blog Section & EclyraSearch**
- **Blog Section**: Users can explore insightful articles on effective recycling techniques, environmental sustainability, and waste management best practices.
- **EclyraSearch**: A smart search feature powered by **Gemini API**, enabling users to quickly find answers to recycling-related queries and optimal waste disposal methods with fast and accurate responses.

---

## 🚀 Getting Started
### **Frontend Setup**
1. Clone the repository:
   ```sh
   git clone https://github.com/simple2226/gsc_frontend.git
   cd gsc_frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the development server:
   ```sh
   npm run dev
   ```

### **Backend Setup**
1. Clone the repository:
   ```sh
   git clone https://github.com/simple2226/gsc_backend.git
   cd gsc_backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the backend server:
   ```sh
   npm run start
   ```

---

## ⚙️ Configuration
### **Frontend Environment Variables**
Create a `.env` file in the project root and add your Firebase config:
```sh
VITE_BACKEND_URL=your-local-api-url
VITE_GOOGLE_MAPS_API_KEY=your-google-map-api
VITE_FIREBASE_API_KEY=your-firebase-api-key
VITE_FIREBASE_AUTH_DOMAIN=your-auth-domain
VITE_FIREBASE_PROJECT_ID=your-project-id
VITE_FIREBASE_DATABASE_URL=your-database-url
VITE_FIREBASE_STORAGE_BUCKET=your-storage-bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your-firebase-message-sender-id
VITE_FIREBASE_APP_ID=your-firebase-app-id
VITE_FIREBASE_MEASUREMENT_ID=your-firebase-measurement-id
```

### **Backend Environment Variables**
Create a `.env` file in the backend root and add:
```sh
PORT=your-local-port
SMTP_HOST=your-smtp-host
SMTP_PORT=your-smtp-port
SMTP_USER=your-smtp-user
SMTP_PASS=your-smtp-pass
DATABASE_URL=your-database-url
```

---

## 🤝 Contributors
Eclyra wouldn't have been possible without the hard work and dedication of its team members:
- **Ayush Ranjan** – Chatbot Integration & Frontend Developer
- **Rohit Khallar** – Backend & Database Architect
- **Ayush Kumar** – Frontend Developer
- **Tanisha Rattan** – UI/UX Designer

### **How We Came Up With This Idea**
The team noticed firsthand how individuals and small businesses struggled with selling scrap, especially electronic waste, due to a lack of proper channels and fair pricing. Seeing people discard valuable e-waste improperly, leading to both environmental hazards and financial loss, we decided to create Eclyra—an AI-powered platform that simplifies scrap selling, ensures transparent pricing, and encourages responsible e-waste disposal. By integrating real-time pricing, chatbot assistance, and community engagement, Eclyra is set to revolutionize the waste management industry.

---

## 📜 License
This project is licensed under the **MIT License**. See the LICENSE file for more details.

