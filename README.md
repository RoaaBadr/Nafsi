# Nafsi - Mental Health Web Application

<p align="center">
  <img src="src/assets/NafsiHomepage.png" alt="Nafsi home page screenshot." />
</p>

## Overview

Nafsi is a comprehensive mental health web application designed to provide users with mental health resources, articles, videos, quizzes, and self-help tools. The platform aims to make mental health support accessible and user-friendly.

## Features

### Core Features
- **Articles Library** - Browse mental health articles on various topics
- **Video Resources** - Watch therapeutic and educational videos
- **Mental Health Quizzes** - Self-assessment quizzes for various conditions
- **User Authentication** - Login/signup functionality with secure authentication
- **User Profile** - Personalized user dashboard
- **Admin Panel** - Content management system for administrators (not implemented in this version)

### Additional Features
- **Eye Tracking** - WebGazer integration for gaze tracking (optional feature)
- **Chatbot** - AI-powered chatbot for mental health support (requires Flowise Embed integration)
- **Psychosis Screening** - Mental health screening tools
- **Mood Tracking** - Track and monitor mood patterns
- **Responsive Design** - Works on mobile, tablet, and desktop

## Tech Stack

### Frontend
- **React** - UI framework
- **Vite** - Build tool and development server
- **React Router** - Client-side routing
- **Redux Toolkit** - State management
- **Axios** - HTTP client
- **Bootstrap / MDB** - UI components and styling
- **Flowise Embed** - Chatbot integration

### Backend
- **Node.js** - Server runtime
- **Express** - Web framework
- **MongoDB** - Database

## Getting Started

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Graduation-project
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to:
```
http://localhost:5173
```

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

## Data Source

The application can use either:
1. **Local Data** - Data stored in `src/data.js` (currently active)
2. **Backend API** - Connect to a backend server for dynamic data

To switch to backend API, update the `useFetch.jsx` hook and related components to fetch from your API endpoints.
