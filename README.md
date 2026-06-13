# HOOPX — Street Ballers Network 🏀

> The world's most premium street sports network. Find, join, and create street games globally.

## 🌟 About The Project

**HOOPX** is a dynamic web application designed for street ballers around the world. From Tokyo to New York, the platform allows players to discover live and upcoming street games near them, join instantly, and build their reputation on city leaderboards.

### ✨ Key Features
- **Find Games:** Browse live and upcoming street games near you. Filter by skill level, location, or time slot.
- **Join or Create:** Tap to join instantly or spin up your own game in under 30 seconds.
- **Build Your Rep:** Earn points for every game played, climb local leaderboards, and unlock badges.
- **Premium UI/UX:** Built with modern design principles featuring liquid-glass distortion effects, smooth animations, and a rich aesthetic.

## 🚀 Built With
- **Frontend:** HTML5, Vanilla CSS, JavaScript
- **Build Tool:** [Vite](https://vitejs.dev/)
- **3D Graphics:** [Three.js](https://threejs.org/)
- **Animations:** [GSAP](https://gsap.com/)

## 📁 Folder Structure

```
street-ballers/
├── public/                  # Static assets served as-is
│   ├── favicon.svg          # Custom HOOPX brand favicon
│   ├── icons.svg            # SVG icon sprite sheet
│   └── models/
│       └── basketball.glb   # 3D basketball model (GLB format)
├── src/
│   ├── main.js              # Application entry — Three.js scene, GSAP animations, interactions
│   └── style.css            # Global styles — liquid-glass effects, layout, responsive design
├── index.html               # Main HTML — hero, stats, how-it-works, footer sections
├── vite.config.js           # Vite build configuration
├── package.json             # Project metadata & dependencies
└── .gitignore               # Git ignore rules
```

## 🛠️ Running Locally

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/RonitkumarSoni/Ball-pulses.git
   ```

2. **Navigate into the directory**
   ```bash
   cd street-ballers
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

## 🌐 Deployment
This project is optimized for deployment on [Vercel](https://vercel.com/). Connect your GitHub repository to Vercel and it will automatically deploy using Vite's build settings.

## 📜 License
Distributed under the MIT License. Copyright © 2026 HOOPX. All rights reserved.
