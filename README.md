<div align="center">

# 🏛️ Ravindra's IAS Academy

**A premium, immersive coaching web portal for UPSC Civil Services Examination (CSE) and other competitive government exams (State PCS, SSC, Judiciary, etc.). Built using React, GSAP, and Three.js, it offers an interactive learning experience with custom mind-maps and performance tracking.**

[![Live Demo](https://img.shields.io/badge/Demo-Live%20on%20Render-34D058?style=for-the-badge&logo=render&logoColor=white)](https://visual-identity-e2yc.onrender.com)
[![React](https://img.shields.io/badge/React-19.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org)
[![GSAP](https://img.shields.io/badge/GSAP-3.14-green?style=for-the-badge&logo=greensock&logoColor=white)](https://gsap.com)
[![Vite](https://img.shields.io/badge/Vite-8.0-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)

<p align="center">
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-key-features">Key Features</a> •
  <a href="#-project-architecture">Project Structure</a> •
  <a href="#-getting-started">Getting Started</a>
</p>

---

</div>

## 🌐 Live Application

Access the deployed site here:  
👉 **[https://visual-identity-e2yc.onrender.com](https://visual-identity-e2yc.onrender.com)**

---

## 🛠️ Tech Stack & Architecture

This application leverages modern frontend web technologies to create a high-performance, visually stunning experience:

| Technology | Purpose | Key Integration Details |
| :--- | :--- | :--- |
| **React (v19)** | UI Library | Component-driven architecture, hooks, and responsive lifecycle management. |
| **Vite (v8)** | Build Tool | Superfast hot-reloading (HMR) and optimized building pipeline. |
| **Three.js & React Three Fiber** | 3D Graphics | Renders a rich 3D space (`Canvas`, `PerspectiveCamera`, text meshes, and image planes). |
| **@react-three/drei** | 3D Helpers | Implements advanced OrbitControls, PerspectiveCamera helpers, and text extrusion. |
| **GSAP (GreenSock)** | Animations | Orchestrates complex UI transitions, timeline animations, and smooth custom cursor tracking. |
| **React Router (v7)** | Client-Side Routing | Provides clean navigation paths (`/courses`, `/toppers`, `/current-affairs`, `/study-material`, and details pages). |
| **Custom CSS** | Design System | Fully customized layout with custom variables, smooth transitions, glassmorphism UI, and responsive flex/grid layouts. |

---

## ✨ Key Features

*   **🌌 Dynamic 3D Parallax Scroll:** A custom `CameraScroll` component listens to mouse-wheel scrolls and updates camera depth (`z` axis) and rotation smoothly inside the Three.js Canvas environment.
*   **💫 Seamless Timelines:** Micro-interactions, hover configurations, and animations powered by **GSAP** for a responsive, interactive user experience.
*   **🎨 Custom Interactive Cursor:** A lag-free custom cursor following the user's mouse with inertial dampening.
*   **🤖 AI-Powered Counselling:** Dedicated component to guide students through course recommendations.
*   **🏆 Toppers & Success Showcase:** Fully responsive carousel highlight cards displaying recent academy accomplishments.
*   **📱 Mobile-First Breakpoints:** Carefully tuned breakpoints from 360px up to 1200px+ ensuring layouts render flawlessly on all viewports.

---

## 📁 Project Architecture

```text
├── public/                 # Static public assets
│   ├── fonts/              # Custom brand typography
│   ├── images/             # Images (Toppers, course banners, gallery)
│   └── svg/                # Brand social icons and logos
├── src/
│   ├── assets/             # Bundled react logos and media
│   ├── components/         # Modular user interface components
│   │   ├── AICounselling.jsx   # AI Guidance module
│   │   ├── AboutUs.jsx         # Section detailing mission
│   │   ├── Courses.jsx         # UPSC, JEE, BPSC courses list
│   │   ├── CourseDetail.jsx    # Dynamically routed course details
│   │   ├── CustomCursor.jsx    # GSAP mouse tracker
│   │   ├── HomePage.jsx        # Landing page content wrapper
│   │   ├── Scene.jsx           # Three.js 3D canvas setup & parallax camera
│   │   └── Toppers.jsx         # Academy success journey components
│   ├── App.jsx             # React Router structure & primary layout
│   ├── index.css           # Brand tokens, global styles, and responsive themes
│   └── main.jsx            # Application initialization
├── index.html              # Core HTML structure
├── vite.config.js          # Vite setup & build optimization rules
└── package.json            # Scripts, dependencies, and configuration
```

---

## ⚙️ Getting Started

Follow these instructions to run the application locally on your machine:

### 1. Clone the Repository
```bash
git clone https://github.com/Pushpendra-7-ux/visual-identity.git
cd visual-identity
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the Local Dev Server
```bash
npm run dev
```
Navigate to `http://localhost:5173` in your browser.

### 4. Build for Production
To output optimized static files to `/dist` for hosting:
```bash
npm run build
```

---

## 📄 License

This project is licensed under the MIT License.
