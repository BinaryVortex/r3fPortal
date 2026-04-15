# 🌌 R3F Portal Scene

A beautiful, interactive 3D portal scene built with **React Three Fiber**, **Three.js**, and custom **GLSL Shaders**. This project features a "baked" model with custom lighting effects and particles.

## 🚀 Live Demo & Screenshots

Here is a preview of the portal in action:

<p align="center">
  <img src="./Screenshot 2025-10-05 130851.png" width="45%" alt="Portal View 1" />
  <img src="./Screenshot 2025-10-05 130906.png" width="45%" alt="Portal View 2" />
</p>

<p align="center">
  <img src="./Screenshot 2025-10-05 130916.png" width="30%" alt="Close up" />
  <img src="./Screenshot 2025-10-05 130938.png" width="30%" alt="Shader Detail" />
  <img src="./Screenshot 2025-10-05 131001.png" width="30%" alt="Full Scene" />
</p>

## ✨ Features

- 🎨 **Baked Textures**: High-quality lighting baked directly into the textures for performance and aesthetics.
- 🌀 **Custom Shaders**: A procedural portal effect written in GLSL with time-based animation.
- ✨ **Particle Effects**: Floating sparkles using `@react-three/drei`'s `Sparkles` component.
- 🛠️ **Optimized**: Built with Vite for extremely fast development and bundling.

## 🛠️ Tech Stack

- [React](https://reactjs.org/)
- [Three.js](https://threejs.org/)
- [React Three Fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction) (R3F)
- [React Three Drei](https://github.com/pmndrs/drei)
- [Vite](https://vitejs.dev/)
- GLSL Shaders

## 📦 Getting Started

### Prerequisites

- Node.js (v18+)
- npm / yarn / pnpm

### Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd r3fPortal-master
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## 🏗️ Project Structure

- `src/shaders/`: Custom GLSL vertex and fragment shaders for the portal effect.
- `public/model/`: 3D assets (GLB) and baked textures.
- `Experience.jsx`: The main R3F scene composition.

## 📜 License

MIT
