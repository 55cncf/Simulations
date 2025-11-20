# Heat Transfer Simulation - Conduction

An interactive 3D simulation of heat conduction in materials, built with Three.js.

## Features

- **3D Visualization**: Real-time 3D visualization of heat transfer
- **Material Types**: Compare conductors vs insulators
- **Interactive Controls**: Adjust material properties, lattice settings, and heat sources
- **Movable Hot Object**: Drag and drop heat sources in the simulation
- **Educational Focus**: Learn about electron conduction and phonon vibration

## How to Use

1. **Start Simulation**: Click "Start Simulation" to begin
2. **Adjust Parameters**: Use sliders to modify material properties
3. **Interact**: 
   - Rotate view: Click and drag
   - Zoom: Scroll or pinch
   - Move hot object: Click and drag the orange sphere
   - Grab mode: Press 'G' key for precise hot object positioning
4. **Compare Materials**: Switch between conductor and insulator modes

## Physics Concepts Demonstrated

- **Conductors**: Heat transfer via electron collisions
- **Insulators**: Heat transfer via atomic vibrations (phonons)
- **Thermal Conductivity**: How material properties affect heat flow
- **Temperature Gradients**: Heat flows from hot to cold regions

## Controls

### Material Properties
- Thermal Conductivity
- Vibration Scale
- Material Type (Conductor/Insulator)

### Lattice Settings
- Atom count (X, Y, Z dimensions)
- Atom spacing and size

### Electron Settings (Conductors)
- Electron density and count
- Electron speed and drift

### Heat Sources
- Hot and cold temperature regions
- Ambient temperature
- Movable hot object with adjustable temperature

## Technical Details

- Built with **Three.js** for 3D rendering
- Uses **OrbitControls** for camera manipulation
- Real-time physics simulation
- Responsive design for desktop and mobile

## Deployment

This site is deployed via GitHub Pages. To run locally:
1. Clone the repository
2. Open `index.html` in a web browser
3. No server required - runs entirely client-side

## Browser Compatibility

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

*Note: Requires WebGL support for 3D rendering*
