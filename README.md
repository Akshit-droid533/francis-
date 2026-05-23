# Francis - Interactive Football Game Website

A beautiful, modern website featuring an interactive 3D football game with a powerful backend API.

## 🎮 Features

- **Interactive 3D Football Game** - Play a stunning 3D football game with realistic physics
- **Beautiful UI** - Modern, responsive design with smooth animations
- **RESTful Backend** - Node.js/Express API for game data and scores
- **Real-time Stats** - Track your game statistics and leaderboards
- **Mobile Friendly** - Fully responsive design for all devices
- **Professional Graphics** - High-quality 3D rendering with Three.js

## 🚀 Tech Stack

### Frontend
- **React** - UI framework
- **Three.js** - 3D graphics engine
- **Tailwind CSS** - Styling
- **Vite** - Build tool
- **Axios** - HTTP client

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **MongoDB** - Database (optional)
- **CORS** - Cross-origin resource sharing

## 📁 Project Structure

```
francis-/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Game.jsx
│   │   │   ├── Navigation.jsx
│   │   │   ├── Home.jsx
│   │   │   └── Leaderboard.jsx
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── styles/
│   │       └── index.css
│   ├── public/
│   ├── package.json
│   ├── vite.config.js
│   └── index.html
├── backend/
│   ├── server.js
│   ├── routes/
│   │   ├── gameRoutes.js
│   │   └── playerRoutes.js
│   ├── controllers/
│   │   ├── gameController.js
│   │   └── playerController.js
│   ├── models/
│   │   └── Game.js
│   ├── middleware/
│   │   └── errorHandler.js
│   ├── package.json
│   ├── .env.example
│   └── .gitignore
└── README.md
```

## 🛠️ Installation & Setup

### Backend Setup

```bash
cd backend
npm install
cp .env.example .env
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## 📝 Environment Variables

Create a `.env` file in the backend directory:

```
PORT=5000
NODE_ENV=development
MONGODB_URI=mongodb://localhost:27017/francis
API_URL=http://localhost:5000
```

## 🎮 How to Play

1. Navigate to the home page
2. Click "Play Game" to start the football game
3. Use keyboard controls to move your player
4. Score goals to earn points
5. Check the leaderboard to see top scores

## 🎯 Controls

- **Arrow Keys** - Move player
- **Space** - Kick/Pass
- **Click** - Aim/Shoot

## 📊 API Endpoints

### Game Endpoints
- `POST /api/game/start` - Start a new game
- `POST /api/game/score` - Record a goal
- `GET /api/game/stats/:playerId` - Get player stats

### Player Endpoints
- `GET /api/players/leaderboard` - Get top players
- `POST /api/players/register` - Register player
- `GET /api/players/:id` - Get player info

## 🌐 Deployment

### Deploy Frontend (Vercel/Netlify)
```bash
cd frontend
npm run build
# Deploy the dist folder
```

### Deploy Backend (Heroku/Railway)
```bash
cd backend
git push heroku main
```

## 📸 Screenshots

[Screenshots coming soon]

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**Akshit** - Created with ❤️

---

**Built with React, Three.js, Node.js & Express** ⚡