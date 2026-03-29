# 🚀 AURA - Dynamic Lottie Animation Showcase

[![React](https://img.shields.io/badge/React-19.0-brightgreen)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8.0-orange)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6.0-blue)](https://www.typescriptlang.org/)
[![Lottie](https://img.shields.io/badge/Lottie-0.18-yellow)](https://lottiefiles.com/)

## ✨ Features
- **Smooth Lottie Animations**: Cat rocket, run cycle, skull boy.
- **React + Vite**: Fast HMR & builds.
- **TypeScript**: Type-safe code.
- **Responsive Design**: Works on all devices.
- **Mock Data Integration**: Dynamic content loading.

## 🎥 Live Demo
App running locally at [http://localhost:5173/Aura/](http://localhost:5173/Aura/)

## 📱 App Structure
```mermaid
graph TD
    A[MockData.ts] --> B[App.tsx]
    B --> C[Lottie Components]
    C --> D[Animations: cat, run, skull]
    E[User Interactions] --> B
```

## 🚀 Quick Start
```bash
cd frontend
npm install
npm run dev
```

## 🔧 Deployment
```bash
npm run build
npm run deploy  # Uses gh-pages
```

## 📁 Folder Structure
```
Aura/
├── frontend/     # React Vite app
├── public/       # Assets & animations
├── README.md     # This file!
└── .gitignore
```

## 🤝 Contributing
1. Fork the repo
2. Create branch: `git checkout -b feature`
3. Commit: `git commit -m 'Add feature'`
4. Push: `git push origin feature`
5. Open PR!

## 📄 License
MIT
