# Devansh Patel — Engineering & Creative Technology Portfolio

[![Website](https://img.shields.io/badge/Portfolio-Live%20Demo-22e6ff?style=for-the-badge&logo=vercel&logoColor=white)](https://YOUR-VERCEL-DOMAIN.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dhp65-0077b5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhp65/)
[![GitHub](https://img.shields.io/badge/GitHub-DHP065-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DHP065)

A modern, high-performance, dark celestial-themed personal portfolio showcasing projects at the intersection of **Artificial Intelligence**, **Computer Vision**, **Cybersecurity**, and **Interactive Web Engineering**.

---

## Interactive Experience & Highlights

- **Dynamic Three.js Space Environment:** Real-time geometric icosahedron core, procedural orbital rings, particle dust systems, and mouse-parallax physics.
- **Interactive 3D Holographic Avatar:** WebGL GLTF avatar with smooth orientation decay and cursor-tracking lighting.
- **Mark A Interactive Skills Panel:** Comprehensive technical capability matrix with categorized filters, project mappings, and verified implementation specifications.
- **Orbital Project Deck with 3D Flip Cards:** Double-tap / double-click card flips revealing technical architecture, system specs, and direct GitHub links.
- **360° Holographic Certification Cards:** In-place 3D rotation with synchronized cyan-to-violet light sweeps.
- **Universal Responsive Design:** Optimized across 15 standard, foldable, tablet, laptop, and ultrawide viewports with zero horizontal overflow.
- **WCAG 2.1 AA Compliant:** Accessible touch targets ($\ge 44\text{px}$), screen reader attributes, keyboard navigability, and `prefers-reduced-motion` support.

---

## Technology Stack

- **Core:** HTML5, CSS3, Modern ES6+ JavaScript
- **3D Graphics & WebGL:** [Three.js](https://threejs.org/) (r128), GLTFLoader
- **Animation & Physics:** [GSAP 3](https://greensock.com/gsap/) with ScrollTrigger
- **Typography:** Unbounded, Manrope (Google Fonts)
- **Deployment Platform:** Vercel Static Hosting

---

## Repository Structure

```
.
├── index.html                    # Production single-file application
├── og-image.png                  # Open Graph social sharing card (1200×630px)
├── robots.txt                    # Search crawler indexing rules
├── sitemap.xml                   # Search engine XML sitemap
├── Portfolio_resume_DHP.pdf      # Authoritative verified resume
├── vercel.json                   # Vercel deployment & security headers configuration
├── .gitignore                    # Git exclusion rules
└── models/
    └── portfolio-avatar.glb      # 3D holographic avatar GLTF model
```

---

## Repository

- **Public Repository:** [https://github.com/DHP065/Portfoio](https://github.com/DHP065/Portfoio)
- **Clone:** `git clone https://github.com/DHP065/Portfoio.git`

---

## Local Preview

Because the project loads a 3D avatar model (`.glb`) via WebGL, it must be served through an HTTP server to satisfy browser CORS security requirements for local models.

### Option 1: Python HTTP Server (Built-in)
```bash
python -m http.server 8080
```
Open your browser to: [http://localhost:8080](http://localhost:8080)

### Option 2: Node.js `serve` / `npx`
```bash
npx serve .
```

### Option 3: VS Code Live Server
1. Open this directory in VS Code.
2. Right-click `index.html`.
3. Select **"Open with Live Server"**.

---

## Author & Contact

**Devansh Patel**  
Computer Engineering Student & Creative Technologist  
- **Email:** [devansh655patel@gmail.com](mailto:devansh655patel@gmail.com)  
- **LinkedIn:** [linkedin.com/in/dhp65](https://www.linkedin.com/in/dhp65/)  
- **GitHub:** [github.com/DHP065](https://github.com/DHP065)

---

## License

This project is personal portfolio intellectual property. All rights reserved.  
Source code is made available for evaluation and review purposes.

