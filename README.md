# 🌟 Avinash's 3D Portfolio

> An interactive 3D portfolio showcasing 26 web development projects with an immersive Three.js landing experience

[![Live Demo](https://img.shields.io/badge/🚀-Live%20Demo-success)](https://deep0ctave.github.io/webdev_projects/)
[![Three.js](https://img.shields.io/badge/Three.js-0.160.0-blue)](https://threejs.org/)
[![Projects](https://img.shields.io/badge/Projects-26-orange)](./projects/)

## ✨ Features

- 🎨 **Interactive 3D Landing Page** - Explore projects in an immersive 3D environment
- 🎯 **26 Unique Projects** - From complex physics simulations to simple web apps
- 🏷️ **Smart Categorization** - Filter by Animations, Simulations, Models, Shaders, and Web Apps
- 📱 **Responsive Design** - Optimized for desktop and mobile experiences
- ⭐ **Featured Projects** - Highlighted showcase of best work
- 🎮 **Interactive Controls** - Drag to rotate, scroll to zoom, click to explore

## 🚀 Live Demo

Visit the live portfolio: **[https://deep0ctave.github.io/webdev_projects/](https://deep0ctave.github.io/webdev_projects/)**

## 📁 Project Structure

```
my_one_repo/
├── index.html              # 3D interactive landing page
├── data/
│   └── projects.json       # Project metadata and categories
├── projects/               # All individual projects
│   ├── alien-orb/
│   ├── basic-physics-simulation/
│   ├── bouncing-ball/
│   ├── calculator/
│   ├── door/
│   ├── etch_a_sketch/
│   ├── fox/
│   ├── galaxy/
│   ├── galaxy_v2/
│   ├── haunted-house/
│   ├── hypercube/
│   ├── jenga/
│   ├── name-showcase/
│   ├── particle-wave/
│   ├── portfolio/
│   ├── raging-sea/
│   ├── redbox/
│   ├── rock_paper_scissor/
│   ├── rock_paper_scissor_v2/
│   ├── scroll-based-animation/
│   ├── simple-scene/
│   ├── village_temple_splat/
│   ├── avin-landing-page/
│   ├── avin-recipies/
│   ├── odin-landing-page/
│   └── odin-recipes/
└── README.md
```

## 🎯 Project Categories

### 🌊 Three.js Animations (8 projects)
Dynamic 3D animations and particle effects

- **Galaxy** - Procedurally generated galaxy with particle system ⭐
- **Galaxy V2** - Enhanced version with improved visuals ⭐
- **Particle Wave** - Mesmerizing particle wave animation ⭐
- **Raging Sea** - Realistic ocean waves with custom shaders ⭐
- **Scroll-Based Animation** - 3D animation controlled by scroll position ⭐
- **Bouncing Ball** - Simple ball animation with shadows
- **Red Box Animation** - Basic animation fundamentals

### 🎮 Three.js Simulations (4 projects)
Interactive physics simulations and games

- **Basic Physics Simulation** - Collision detection with sound effects ⭐
- **Jenga Game** - Interactive Jenga with realistic physics ⭐
- **Animated Door** - Realistic door with textures and lighting
- **Haunted House** - Spooky scene with fundamental features

### 🦊 Three.js Models (7 projects)
3D model viewers and showcases

- **Village Temple (Gaussian Splat)** - React Three Fiber with Gaussian splatting ⭐
- **3D Fox Model** - GLTF/GLB model viewer with environment mapping ⭐
- **3D Portfolio** - Interactive portfolio with multiple models ⭐
- **Hypercube** - 4D hypercube visualization ⭐
- **Name Showcase** - 3D text with custom fonts
- **Simple Scene** - Basic starter template

### 🎨 Three.js Shaders (1 project)
Custom shader effects and materials

- **Alien Orb** - Custom shader with Perlin noise ⭐

### 💻 Web Apps (6 projects)
Vanilla JavaScript applications

- **Calculator** - Simple vanilla JS calculator
- **Etch-A-Sketch** - Interactive drawing app
- **Rock Paper Scissors** - Classic game
- **Rock Paper Scissors V2** - Enhanced version with better UI
- **Avin Recipes** - Creative recipe website
- **Odin Recipes** - Recipe site from The Odin Project
- **Avin Landing Page** - Landing page design
- **Odin Landing Page** - Landing page from The Odin Project

⭐ = Featured Project

## 🛠️ Technologies Used

### Core Technologies
- **Three.js** - 3D graphics library
- **WebGL** - Graphics rendering
- **JavaScript (ES6+)** - Core programming
- **HTML5 & CSS3** - Structure and styling

### Build Tools
- **Vite** - Build tool for most Three.js projects
- **React Three Fiber** - For village_temple_splat project

### Libraries & Frameworks
- **Cannon.js** - Physics engine (physics simulation, jenga)
- **GSAP** - Animations (scroll-based projects)
- **OrbitControls** - Camera controls
- **GLTF/GLB Loaders** - 3D model loading

## 🏃‍♂️ Local Development

### Prerequisites
- Modern web browser with WebGL support
- Node.js installed (for local server)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/deep0ctave/webdev_projects.git
   cd webdev_projects
   ```

2. **Start local server with Node.js**
   
   **Option 1: Using npm (recommended)**
   ```bash
   npm start
   ```
   This will start a server on `http://localhost:8000`
   
   **Option 2: Using npx serve directly**
   ```bash
   npx serve -l 8000
   ```
   
   **Option 3: Using http-server**
   ```bash
   npx http-server -p 8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

### Alternative Server Options

**Using Python:**
```bash
python -m http.server 8000
```

**Using VS Code Live Server:**
- Install "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

### Building village_temple_splat

The village_temple_splat project requires building:

```bash
cd projects/village_temple_splat
npm install
npm run build
```

## 🌐 Deployment

### GitHub Pages

1. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from branch
   - Branch: `main` / `master`
   - Folder: `/ (root)`

2. **Update Repository Name**
   
   If your repository name is not the default, update the paths in:
   - All project `index.html` files (update `/projects/` paths)
   - `village_temple_splat/vite.config.js` (update base path)

3. **Wait for Deployment**
   - GitHub will automatically deploy your site
   - Visit: `https://deep0ctave.github.io/webdev_projects/`

### Custom Domain (Optional)

1. Add a `CNAME` file to the root with your domain
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings with custom domain

## 🎨 Visual Design

The landing page features:
- **3D Floating Cards** - Each project displayed on an interactive 3D card
- **SVG Icons** - Unique emoji icons for each project type
- **Category Colors** - Color-coded by project category
- **Particle Background** - Ambient particles for visual depth
- **Hover Effects** - Interactive animations on card hover

## 🎓 Learning Resources

This portfolio demonstrates concepts from:
- **Three.js Journey** by Bruno Simon
- **The Odin Project** - Web development curriculum
- Custom experiments and creative coding

## 🤝 Contributing

This is a personal portfolio, but feel free to:
- Report bugs or issues
- Suggest improvements
- Fork for your own portfolio inspiration

## 📝 License

Individual projects may have different licenses. Please check each project's README for specifics.

## 📧 Contact

- **GitHub**: [@deep0ctave](https://github.com/deep0ctave)

## 🙏 Acknowledgments

- **Bruno Simon** - Three.js Journey course
- **The Odin Project** - Web development curriculum
- **Three.js Community** - Documentation and support
- **You** - For checking out my portfolio! 🚀

---

<div align="center">
  
**Made with ❤️ and Three.js**

[⬆ Back to Top](#-avinashs-3d-portfolio)

</div>
