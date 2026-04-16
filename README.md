# 🌟 Manobendra's 3D Interactive Portfolio

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Threejs](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Framer](https://img.shields.io/badge/Framer-Black?style=for-the-badge&logo=framer&logoColor=blue)

Welcome to the source code for my 3D personal portfolio! This project leverages the power of React, Three.js, and Framer Motion to create a highly interactive, animated, and visually appealing web experience.

## ✨ Features

- **Interactive 3D Graphics**: Implemented using `three.js` and `@react-three/fiber` for breathtaking models and canvas elements.
- **Smooth Animations**: High-performance UI and component transitions powered by `framer-motion`.
- **Responsive Design**: Flawlessly scaling from desktop monitors down to mobile screens using Tailwind CSS.
- **Interactive Timeline**: A robust vertical timeline showcasing my experience.
- **Working Contact Form**: Integrated with EmailJS for direct client communication.

## 🛠️ Tech Stack

- **Framework**: [React.js](https://reactjs.org/) + [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **3D Rendering**: [Three.js](https://threejs.org/) & [React Three Fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Additional Libraries**: `react-vertical-timeline-component`, `react-tilt`, `maath`

## 🚀 Getting Started

If you want to run this project locally, follow the steps below:

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/en/) installed on your machine.

### Installation

1. **Clone the repository** (or download the source):
   ```bash
   git clone <your-repo-url>
   cd Manobendra_portfolio-main
   ```

2. **Install all dependencies**
   > *Note: We use the `--legacy-peer-deps` flag to ensure compatibility between some specific React Three Fiber / Three.js library versions!*
   ```bash
   npm install --legacy-peer-deps
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **View your site**
   Open `http://localhost:5173` in your browser. Any changes you make in the code will automatically be reflected in the browser!

### Building for Production

When you are ready to deploy your site directly or want to generate the optimized files:
```bash
npm run build
```
This will create a `dist` folder natively that is ready for production.

## 🚀 Deployment (Vercel)

This project is exceptionally optimized for hosting on Vercel. 
Simply push your repository to GitHub, link it on the Vercel dashboard, and leave the default settings (**Framework:** Vite, **Build Command:** `npm run build`, **Install Command:** `npm install --legacy-peer-deps`).

---
*Created and maintained by Manobendra.*
