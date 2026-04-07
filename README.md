# Mission 3 - Project L5

Welcome to Mission 3! This project is part of the Level 5 advanced track.

## 📋 Overview

This mission implements a **Full-Stack Application** with both backend and frontend components. The project demonstrates building complete web applications with API integration, testing, and modern development practices.

## 📁 Project Structure

```
mission-3/
├── backend/
│   ├── api.js               # API definitions
│   ├── server.js            # Express server
│   ├── package.json         # Backend dependencies
│   └── tests/               # Test suites
└── frontend/
    ├── src/
    │   ├── App.jsx          # Main component
    │   ├── main.jsx         # Entry point
    │   ├── index.css        # Styles
    │   └── App.css
    ├── public/              # Static assets
    ├── index.html           # HTML template
    ├── package.json         # Frontend dependencies
    ├── vite.config.js       # Vite configuration
    ├── eslint.config.js     # ESLint configuration
    └── README.md            # Frontend documentation
```

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- npm or yarn

### Backend Setup

```bash
cd backend
npm install
npm start
```

The backend server will start on the configured port (default: 3000)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Running Tests

```bash
cd backend
npm test
```

### Production Build

```bash
# Backend
cd backend
npm start

# Frontend
cd frontend
npm run build
npm run preview
```

## 🛠️ Technologies Used

**Backend:**
- Node.js/Express
- JavaScript
- Testing framework
- REST API

**Frontend:**
- React
- Vite
- CSS
- ESLint

## ✨ Features

- Complete backend API
- React-based frontend
- API integration
- Comprehensive testing
- Responsive design
- Error handling and validation

## 📡 API Integration

The frontend communicates with the backend API. Ensure the backend is running before starting the frontend. By default:
- Backend: `http://localhost:3000`
- Frontend: `http://localhost:5173`

## 📝 Environment Configuration

Create `.env` files as needed:

**Backend .env:**
```
PORT=3000
NODE_ENV=development
```

**Frontend .env:**
```
VITE_API_URL=http://localhost:3000
```

## 📄 License

This project is part of the Mission Ready Level 5 Advanced track.
