# 🏛️ Ravindra's IAS Academy

A premium, interactive web application for **Ravindra's IAS Academy** built with **React**, **Vite**, and **Three.js**. It features smooth animations powered by **GSAP**, custom user interface components, and a modern responsive design designed to showcase academy courses, toppers, study materials, and AI-driven counselling.

[![Live Demo](https://img.shields.io/badge/Demo-Live%20on%20Render-brightgreen?style=for-the-badge&logo=render)](https://visual-identity-e2yc.onrender.com)
[![React](https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-8-purple?style=for-the-badge&logo=vite)](https://vitejs.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 🚀 Live Application
Check out the live deployment of the application here:
🔗 **[https://visual-identity-e2yc.onrender.com](https://visual-identity-e2yc.onrender.com)**

---

## ✨ Key Features

- **🌐 Interactive 3D Elements:** Immersive 3D scene elements powered by Three.js (`@react-three/drei`) to engage users.
- **💫 Fluid Animations:** Responsive scroll animations, hover transitions, and carousel effects powered by **GSAP**.
- **🤖 AI Counselling:** Integrated interactive AI counselling interface to guide prospective students.
- **📚 Academic Materials:** Structured showcases for detailed UPSC, BPSC, SSC courses, current affairs updates, and study materials.
- **🏆 Success Stories:** Responsive, animated Toppers showcase highlighting past achievements.
- **🎨 Modern UI/UX:** Features a custom cursor, modern typography, glassmorphism design elements, and a clean interface.
- **📱 Fully Responsive:** Adaptive design tailored for mobile, tablet, and desktop devices.

---

## 🛠️ Tech Stack

- **Frontend Core:** [React](https://react.dev/) & [Vite](https://vitejs.dev/) (Fast HMR)
- **3D Graphics:** [Three.js](https://threejs.org/) & [@react-three/drei](https://github.com/pmndrs/drei)
- **Animation:** [GSAP](https://gsap.com/) (GreenSock Animation Platform)
- **Routing:** [React Router](https://reactrouter.com/)
- **Styling:** Custom CSS (Modern responsive design with CSS custom properties)

---

## 📁 Repository Structure

```text
├── public/                 # Static assets (images, vectors, fonts, icons)
│   ├── fonts/              # Custom brand fonts
│   ├── images/             # Gallery and topper images
│   └── svg/                # Vector assets
├── src/
│   ├── assets/             # Brand logos and base assets
│   ├── components/         # Reusable UI components
│   │   ├── AICounselling.jsx
│   │   ├── AboutUs.jsx
│   │   ├── CourseDetail.jsx
│   │   ├── HomePage.jsx
│   │   ├── Navbar.jsx
│   │   ├── Toppers.jsx
│   │   └── ...
│   ├── App.jsx             # Main routing and layout
│   ├── index.css           # Global stylesheet and design tokens
│   └── main.jsx            # React entrypoint
├── index.html              # HTML shell
├── vite.config.js          # Vite configuration
└── package.json            # Dependencies and scripts
```

---

## ⚙️ Getting Started

To run the application locally, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/Pushpendra-7-ux/visual-identity.git
cd visual-identity
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the Development Server
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:5173` (or the port specified in your console).

### 4. Build for Production
To build the static assets for hosting:
```bash
npm run build
```
This will generate a production-ready `dist` folder.

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
