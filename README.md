# Dogstudio 3D WebGL Clone

A high-performance, interactive 3D clone of the award-winning Dogstudio agency website, built to showcase complex 3D rendering and scroll-triggered animations in a modern web environment.

**🔗 [View Live Demo Here](https://dogstudio-clone-ashy.vercel.app/)**

---

### ⚠️ Disclaimer
**This is an educational clone built purely for technical practice and portfolio demonstration.** All original designs, intellectual property, 3D assets, and branding belong exclusively to [Dogstudio / DEPT®](https://dogstudio.co/). 

---

### 🛠️ Tech Stack
*   **Framework:** React + Vite
*   **3D Rendering:** Three.js, React Three Fiber (R3F), React Three Drei
*   **Animations:** GSAP (ScrollTrigger)
*   **Styling:** Vanilla CSS

### ✨ Key Technical Features
*   **Scroll-Driven 3D Animation:** Integrated GSAP's ScrollTrigger with React Three Fiber to bind the camera position and the 3D dog model's rotation/scale directly to the user's scroll progress.
*   **Custom Shader Materials:** Overrode standard Three.js fragment shaders (`onBeforeCompile`) to achieve smooth, liquid-like transitions between different Matcap textures on hover.
*   **Dynamic Asset Loading:** Utilized GLTF loaders and optimized texture mapping to render high-fidelity 3D objects with environmental lighting.
*   **Responsive UI Overlay:** Built a fully responsive HTML overlay that sits on top of the webGL canvas without blocking pointer events, perfectly matching the original editorial layout.

