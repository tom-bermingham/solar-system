# Interactive Solar System Visualization

A web-based 3D visualization of our solar system built with Three.js, featuring interactive planets, moons, and realistic textures.

## Features

- **Realistic Planet Models**: All eight planets of our solar system with high-resolution textures
- **Natural Orbits**: Planets and moons orbit with different speeds and distances
- **Interactive Navigation**: 
  - Click on any planet or moon to focus the camera on it
  - Drag to rotate the view
  - Scroll to zoom in/out
  - Hover over celestial bodies to see interactive cursors
- **Detailed Elements**:
  - Glowing sun with corona effect
  - Saturn's rings with varying opacity
  - Multiple moons for various planets
  - Planet and moon labels
  - Orbital paths
  - Starfield background

## Technical Details

- Built with Three.js for 3D rendering
- Uses ES6 modules
- Implements custom shaders for sun glow effect
- Features smooth camera transitions
- Includes high-resolution planet textures
- Responsive design that adapts to window size

## Usage

1. Clone the repository
2. Ensure you have the planet textures in a `/textures` directory:
   - `8k_sun.jpg`
   - `8k_mercury.jpg`
   - `8k_venus_surface.jpg`
   - `8k_earth_daymap.jpg`
   - `8k_mars.jpg`
   - `8k_jupiter.jpg`
   - `8k_saturn.jpg`
   - `2k_uranus.jpg`
   - `2k_neptune.jpg`
3. Open `index.html` in a web server (local or hosted)

## Controls

- **Left Click + Drag**: Rotate view
- **Scroll**: Zoom in/out
- **Click Planet/Moon**: Focus camera on the selected body
- **Click Label**: Focus on the associated celestial body

## Dependencies

- Three.js (v0.159.0)
- OrbitControls module
- ES Module Shims for module support

## Notes

- Planet sizes and orbital distances are not to scale for better visualization
- Orbital speeds are approximated for visual appeal
- Textures should be placed in a `/textures` directory 

## Credits

- Planet and sun textures are from [Solar System Scope](https://www.solarsystemscope.com/textures/), who provide high quality space textures for educational and non-commercial use 