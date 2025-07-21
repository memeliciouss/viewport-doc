# **viewport** /memelicious  
### A window into my world  

##  Objective  
A playful, retro-themed web desktop inspired by **Windows 95** that serves as both a personal portfolio and a fun interactive experience.  
It mirrors how I think, build, and design — blending aesthetic nostalgia with modern web development.

> The interface feels more like an operating system than a static page — playful, alive, and dynamic.

---

## 🛠️ Built With  
- **Next.js** (React framework)
- **Firebase Realtime Database** 
- **Vercel** for hosting
- **Custom CSS**
- **Git** for version control  

---

## 📚 Libraries  
- [`WinBox.js`](https://nextapps-de.github.io/winbox/) – Modern desktop window manager  
- [`Three.js`](https://threejs.org/) – WebGL 3D graphics  
- [`@react-three/fiber`](https://docs.pmnd.rs/react-three-fiber/) – React renderer for Three.js  
- [`@react-three/drei`](https://docs.pmnd.rs/drei/) – Helpers for react-three-fiber  

---

## 🎨 Enhancements & Embeds  
- **Sketchbook** – Personal artwork showcase  
- **Pipes** – Remake of Windows 3D Pipes screensaver by [1j01](https://github.com/1j01)  
- **Paint** – MS Paint remake via [jspaint.app](https://jspaint.app)  
- **Pac-Man** – Arcade remake by [masonicGIT](https://github.com/masonicGIT)  
- **Minesweeper** – XP-style clone by [ziebelje](https://github.com/ziebelje)  
- **Old Google 1998** – Embedded via Neocities  

---

## Project Structure (simplified)
```bash
viewport/
├── .gitignore
├── next.config.ts
├── package.json
├── public/
│   ├── clippy-agents/
│   │   ├── clippy/
│   │   │   ├── * clippy assets
│   │   ├── hamster/
│   │   │   ├── * hamster assets
│   │   ├── milkcarton/
│   │   │   ├── * carton assets
│   │   └── ufo/
│   │       ├── * ufo assets
│   ├── cursors/
│   │   ├── *cursors
│   ├── customui/
│   │   ├── controls/
│   │   │   ├── close.webp
│   │   │   ├── cross.webp
│   │   │   ├── max.webp
│   │   │   └── min.webp
│   │   ├── winbox.min.css
│   │   ├── winbox.min.js
│   │   └── windows-theme.css
│   ├── data/
│   │   ├── apps.json
│   │   ├── ascii/
│   │   │   ├── * ascii txt assets
│   │   ├── crt.webp
│   │   └── dither.webp
│   ├── favicon.ico
│   ├── fonts/
│   │   └── windows.ttf
│   ├── icons/
│   │   ├── * icons webp assets
│   ├── mines/
│   │   ├── css/
│   │   │   └── minesweeper.css
│   │   ├── image/
│   │   │   ├── sprite.png
│   │   │   └── v/
│   │   │       └── v_sprite.png
│   │   ├── index.html
│   │   └── js/
│   │       ├── face.js
│   │       ├── grid.js
│   │       ├── minesweeper.js
│   │       ├── rocket.12.06.js
│   │       ├── seedrandom.js
│   │       ├── ssd.js
│   │       └── tile.js
│   ├── pipes/
│   │   ├── candycane.png
│   │   ├── OrbitControls.js
│   │   ├── screensaver.js
│   │   ├── sri-fallback.js
│   │   ├── TeapotBufferGeometry.js
│   │   └── three.min.js
│   ├── sketchbook/
│   │   ├── * sketchbook assets as webp
│   ├── threejs/
│   │   ├── barge.wav
│   │   ├── chime.wav
│   │   ├── normal.webp
│   │   ├── nx.webp
│   │   ├── ny.webp
│   │   ├── nz.webp
│   │   ├── px.webp
│   │   ├── py.webp
│   │   ├── pz.webp
│   │   ├── respawn_anchor.ogg
│   │   ├── star_night.hdr
│   │   ├── weeping_angel.glb
│   │   └── winter_city.hdr
│   └── win95.mp3
├── README.md
├── src/
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   ├── about.tsx
│   │   ├── AddressView.tsx
│   │   ├── Alert.tsx
│   │   ├── AsciiObserver.tsx
│   │   ├── Boot.tsx
│   │   ├── CatGPT.tsx
│   │   ├── ClippyAgent.tsx
│   │   ├── contextMenu.tsx
│   │   ├── customize.tsx
│   │   ├── deskapp.tsx
│   │   ├── IncrementVisits.tsx
│   │   ├── Minesweeper.tsx
│   │   ├── Orbs.jsx
│   │   ├── Pipes.tsx
│   │   ├── Projects.tsx
│   │   ├── ReadVisits.tsx
│   │   ├── RunBox.tsx
│   │   ├── sketchbook/
│   │   │   ├── Book.jsx
│   │   │   ├── Experience.jsx
│   │   │   ├── interface.jsx
│   │   │   └── sketchbook.tsx
│   │   ├── startmenu.tsx
│   │   ├── taskbar.tsx
│   │   ├── TechStack.tsx
│   │   ├── ThisPC.tsx
│   │   ├── WeepingAngel.jsx
│   │   └── WindowManager.tsx
│   ├── firebase.js
│   └── styles/
│       ├── Typewriter.tsx
│       └── wallpaper.css
├── tsconfig.json
└── yarn.lock

