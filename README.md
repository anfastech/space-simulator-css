<img src="https://see.fontimg.com/api/rf5/5YWa/MDljYjFlZTFhMzQ4NDAwZWIxN2NjNThjMmMwYmE0ZmMub3Rm/WHBsb3Jlcg/emperor-of-japan-hollow.png?r=fs&h=107&w=1000&fg=ffffff&bg=000000&tb=1&s=107" />

<img width="563" alt="image" src="https://github.com/user-attachments/assets/43afba76-97b4-44cf-872b-06ade7b3da25" />

A user-friendly solar system explorer built entirely with CSS, providing an interactive and visually appealing experience to explore the planets in our solar system. The application showcases advanced CSS techniques including z-index layering, 3D transforms, and animations to create an immersive space exploration interface.

## Tech Stack

<div style="display: flex; align-items: center; gap: 8px; flex-wrap: wrap;">
  <img src="https://skillicons.dev/icons?perline=7&theme=dark&i=html" alt="Tech Stack Icons" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" style="height: 48px; width: auto;" />
</div>

- **HTML5** - Semantic markup structure
- **CSS3** - Advanced styling with 3D transforms, animations, and z-index layering
- **Font Awesome** - Icon library for enhanced UI elements
- **Google Fonts (Montserrat)** - Typography styling

## Features

- **Advanced CSS Z-Index Management:** Utilizes the `z-index` property in a powerful way to create layered visual effects and proper stacking contexts for planets and UI elements
- **Interactive Planet Explorer:** Click on any planet from the navigation menu to view detailed information and explore the solar system
- **3D CSS Transforms:** Leverages CSS 3D transforms (`transform-style: preserve-3d`) to create depth and spatial relationships between celestial bodies
- **Smooth Animations:** Planet rotations, orbital paths, and transitions are handled through CSS animations and transitions
- **Responsive Design:** Adapts to different screen sizes while maintaining the immersive space exploration experience
- **Visual Planet Information:** Each planet displays its distance from the sun (in AU - Astronomical Units) and includes descriptive information

## How It Works

The solar system simulator uses pure CSS to create an interactive exploration experience through several key mechanisms:

### Layering System

The application employs a sophisticated z-index stacking system where each planet and its associated UI elements are positioned on different layers. This allows for proper visual hierarchy and ensures that interactive elements (like planet menus) appear above the solar system visualization while maintaining the depth perception of the 3D space.

### 3D Transform Architecture

Each planet is contained within a `.solar_systm` container that uses `transform-style: preserve-3d`, enabling true 3D transformations. Planets are positioned using absolute positioning and CSS transforms to create their orbital relationships, while maintaining the ability to rotate and animate in 3D space.

### Radio Button Navigation

The planet selection system uses HTML radio buttons with custom-styled labels. When a planet is selected, CSS selectors (`:checked` pseudo-class) trigger visual changes, showing the selected planet's information panel and adjusting the view to focus on that celestial body.

### Animation System

Planetary rotations and orbital movements are achieved through CSS keyframe animations. Each planet has its own animation timing and duration, creating a realistic sense of movement and rotation speed relative to their actual characteristics.

## Project Structure

```text
space-simulator-css/
├── index.html          # Main HTML file with planet structure
├── src/
│   ├── style.css      # Core styling and planet definitions
│   ├── main.css       # Additional styles and layout
│   └── black.jpg      # Background image asset
└── README.md          # Project documentation
```

## How to Run

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No server or build tools required - runs directly in the browser

### Local Setup

1. Clone the repository or download the project files.

2. Navigate to the project directory.

3. Open `index.html` in your web browser:
   - **Option 1:** Double-click the `index.html` file
   - **Option 2:** Right-click and select "Open with" your preferred browser

### Usage

Once the application loads:

- Click on any planet name in the navigation menu (Mercury, Venus, Earth, etc.) to select and view that planet
- Each planet displays its distance from the sun in Astronomical Units (AU)
- Explore the detailed information panels that appear when selecting different planets
- The solar system visualization updates dynamically based on your selection

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or create a pull request.

<hr>

**Thank You**

[![GitHub](https://img.shields.io/badge/GitHub-anfastech-black?style=flat&logo=github)](https://github.com/anfastech)
