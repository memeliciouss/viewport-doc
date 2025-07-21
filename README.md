# **viewport**
*A window into my world*  
A playful, retro-themed web desktop inspired by Windows 95 that serves as both a fun website and a personal portfolio, mirroring how I think, build, and design.
Blending design and interactivity, making the website feel more like an operating system than a static page, playful and alive.

---

## Built With  
- **Next.js** (React framework)
- **Firebase Realtime Database** 
- **Vercel** for hosting
- **Custom CSS**
- **Git** for version control  


## Libraries  
- [`WinBox.js`](https://nextapps-de.github.io/winbox/) – Modern desktop window manager  
- [`Three.js`](https://threejs.org/) – WebGL 3D graphics  
- [`@react-three/fiber`](https://docs.pmnd.rs/react-three-fiber/) – React renderer for Three.js  
- [`@react-three/drei`](https://docs.pmnd.rs/drei/) – Helpers for react-three-fiber  


## Enhancements & Embeds  
- **Sketchbook** – Personal artwork  
- **Pipes** – Remake of Windows 3D Pipes screensaver by [1j01](https://github.com/1j01)  
- **Paint** – MS Paint remake via [jspaint.app](https://jspaint.app)  
- **Pac-Man** – Arcade remake by [masonicGIT](https://github.com/masonicGIT)  
- **Minesweeper** – XP-style clone by [ziebelje](https://github.com/ziebelje)  
- **Old Google 1998** – Embedded via Neocities  
- **3D models from Sketchfab**
        [WeepingAngel](https://skfb.ly/pnPxB)
        [Cubicle](https://skfb.ly/prP6R)
        [Turtle](https://skfb.ly/pwXMA)
                    

---

## Project Structure
```bash
viewport/
├── .gitignore
├── next.config.ts
├── package.json
├── public/
│   ├── clippy-agents/
│   │   ├── clippy/
│   │   ├── hamster/
│   │   ├── milkcarton/
│   │   └── ufo/
│   ├── cursors/
│   ├── customui/
│   │   ├── controls/
│   │   ├── winbox.min.css          # External (WinBox UI styles)
│   │   ├── winbox.min.js           # External (WinBox JS lib), customized
│   │   └── windows-theme.css       # Custom
│   ├── data/
│   │   ├── apps.json
│   │   ├── ascii/
│   │   ├── crt.webp
│   │   └── dither.webp
│   ├── favicon.ico
│   ├── fonts/
│   │   └── windows.ttf             # W95FA font
│   ├── icons/
│   │   └── *.webp                  # External icon pack (from Internet Archive)
│   ├── mines/                      # Embedded Minesweeper by ziebelje
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
│   ├── pipes/                      # Windows 3D Pipes remake by 1j01
│   │   ├── candycane.png
│   │   ├── OrbitControls.js        # External (Three.js helper)
│   │   ├── screensaver.js
│   │   ├── sri-fallback.js
│   │   ├── TeapotBufferGeometry.js
│   │   └── three.min.js            # External (Three.js lib)
│   ├── sketchbook/
│   │   └── * personal sketchbook art (original, webp)
│   │   ├── office.glb              # 3D model from Sketchfab: https://skfb.ly/prP6R
│   │   └── turtle.glb              # 3D model from Sketchfab: https://skfb.ly/pwXMA
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
│   │   ├── star_night.hdr          # HDRI
│   │   ├── weeping_angel.glb       # 3D model from Sketchfab: https://skfb.ly/pnPxB
│   │   └── winter_city.hdr         # HDRI
│   └── win95.mp3                   # Boot sound
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


