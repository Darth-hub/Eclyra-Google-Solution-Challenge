# Eclyra-Google-Solution-Challenge
Team Eclyra's project repository for GSC 2025

Frontend Repository Link: [Eclyra Frontend] (https://github.com/simple2226/gsc_frontend)  
Backend Repository Link: [Eclyra Backend] (https://github.com/simple2226/gsc_backend)  

## Overview  

Eclyra is leading the way in creating a sustainable and profitable solution for both individuals and businesses. Our platform bridges the gap between scrap sellers and scrap collectors, ensuring that recyclable materials don’t go to waste but instead contribute to a circular economy.The project utilizes ReactJS for the frontend, Firebase for authentication, real-time updates, and hosting, Tailwind CSS for styling, and firebase-firestore for data storage.In addition, we've also integrated AI/ML into our site, by utilising an Dialogflow CX and Vertex AI allowing users to access the Eclyra eazily.

## Table of content

1. [Getting Started](#GettingStarted)

## Getting Started

### Installation

To set up Eclyra's frontend locally, follow these steps:

1. Clone the repository:
```
git clone https://github.com/simple2226/gsc_frontend.git
cd gsc_frontend
```

2. Install Dependencies:
```
npm install
```

To set up Eclyra's backend locally, follow these steps:

```Clone the repository:
git clone https://github.com/simple2226/gsc_backend.git
cd gsc_backend
```

```Install Dependencies:
npm install
```

## Configuration

- To initialise and configure , follow these steps:

  1. Create a firebase project here.

  2. The service account key will be made available if required. Without it, you will not be able to run the Firebase Admin SDK locally.

  3. Create a .env file in the project root of your frontend and add your Firebase config:

```
VITE_BACKEND_URL = your-local-api-url
VITE_GOOGLE_MAPS_API_KEY = your-google-map-api
VITE_FIREBASE_API_KEY= your-firebase-api-key
VITE_FIREBASE_AUTH_DOMAIN= your-auth-domain
VITE_FIREBASE_PROJECT_ID= your-project-id
VITE_FIREBASE_DATABASEURL= your-database-url
VITE_FIREBASE_STORAGE_BUCKET= your-storage-bucket
VITE_FIREBASE_MESSAGING_SENDER_ID= your-firebase-message-sender-id
VITE_FIREBASE_APP_ID= your firebase-app-id
VITE_FIREBASE_MEASUREMENT_ID= your-firebase-measurement-id
```

 4. Create a .env file in the project root of your backend and add your Firebase config:

```
PORT = your-local-port
SMTP_HOST= your-smtp-host
SMTP_PORT= your-smtp-port
SMTP_USER= your-smtp-user
SMTP_PASS= your-smtp-pass
DATABASE_URL= your-database-url
```

## Usage

 1. Run the development server for the frontend:

```
npm run dev
```

2. To run development server for the backend:

```
npm run start
```

## Key Highlights

## Tech Stack

Eclyra is built using the following technologies:

- **Vite React** : A modern frontend development stack that uses Vite as a fast build tool and React as the UI framework.

- **Firebase** : A comprehensive platform for building web and mobile applications, including authentication and real-time database features.

- **Tailwind** : A utility-first CSS framework for building modern designs.

- **Firebase-Firestore** : Firebase Firestore is a cloud-based NoSQL database from Google, designed for real-time syncing and scalability.

### Frontend

- **Vite React** : Our frontend is primarily built with Vite + React, providing a dynamic and responsive user interface.

- **Tailwind CSS** : Tailwind CSS is used for styling, enabling a streamlined and customizable design approach.

- **Mantine UI** : Mantine UI is a modern React component library that provides beautiful, accessible, and customizable UI components for building fast and responsive web applications.

- **Firebase Authentication** : Provides secure user authentication for Eclyra.

### Backend

- **Firebase-Firestore** : Firebase Firestore helps your backend by providing a scalable, real-time NoSQL database that simplifies data storage, retrieval, and synchronization.

- **Node.js Express** : Node.js Express is a lightweight and fast web framework for Node.js. It provides easy routing, middleware support, and a flexible API to build RESTful services.

### AI/Chat Bot 

- **Vertex AI and DialogFlow** : AI chatbot on Eclyra enhances user experience by guiding scrap sellers and collectors, answering queries instantly, assisting with pickups, and providing recycling insights.

### APIs

- **Google Maps api** : The Google Maps API helps Eclyra by enabling location-based services, such as accurate scrap pickup locations, route optimization for collectors, and real-time navigation.

- **Gemini api** : Improve user interactions and streamline the scrap selling and collection process.

### Additional Tools

- **npm** : The package manager for JavaScript, used for installing and managing project dependencies.

- **Git** : Version control system for tracking changes in the source code.

- **Google Cloud** : For hosting our website, cloud storage, authentication, and Maps.

## Development Environment

To set up your development environment, refer to the Getting Started section.

Thank you to the communities behind these technologies for making EcoBloom possible!









