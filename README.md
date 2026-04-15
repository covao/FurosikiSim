# FurosikiSim
![Demo Image](https://covao.github.io/FurosikiSim/demo.png)

## Overview
FurosikiSim is a browser-based cloth folding and box wrapping simulator with simple 3D physics, an interactive ParamUI panel, and a macro-driven auto simulation mode.

## Quick Start
Repository:
https://github.com/covao/FurosikiSim

GitHub Pages:
https://covao.github.io/FurosikiSim/FurosikiSim.html

Place `FurosikiSim.html` and `paramui.js` in the same folder, then open `FurosikiSim.html` in a modern browser. You can also publish the repository with GitHub Pages.

## Features
- Real-time cloth interaction in a 3D view
- Multiple grab modes for folding and lifting
- Box placement, selection, resize, and deletion
- Box wrapping action for wrapping cloth around a box
- Adjustable cloth parameters such as mesh resolution, weight, bendability, stretchability, and friction
- Adjustable floor friction and floor texture
- ParamUI-based control panel for editing parameters from a structured UI
- Auto Simulation group with repeat count and a one-click randomized wrap demo
- ParamUI macro execution that automatically changes parameters, resets the cloth, wraps the box, and repeats the sequence
- Improved slider visibility in the ParamUI panel

## Requirements
- A modern web browser
- WebGL enabled
- Recommended: latest Chrome, Edge, Firefox, or Safari

## Installation
```bash
git clone https://github.com/covao/FurosikiSim.git && cd FurosikiSim
```

## Uninstallation
```bash
rm -rf FurosikiSim
```

## Usage
Open `FurosikiSim.html` in your browser to start the simulator. Use the ParamUI panel on the left to change interaction mode, cloth settings, floor settings, object settings, and wrapping parameters.

### Manual simulation
Drag the cloth or a selected box to interact with the scene. Use the wrapping controls to place a box at the center and wrap the cloth around it. Adjust cloth strength-related parameters to change how strongly the cloth resists stretching and bending.

### Auto simulation
Open the `Auto Simulation` group in the ParamUI panel, set `Repeat Count`, and press `Run Auto Simulation`.

Each cycle uses the ParamUI macro feature to:
1. Randomize key wrapping and cloth parameters
2. Reset the cloth state
3. Wrap the box automatically
4. Repeat for the requested number of cycles

The runtime status text shows the current progress and completion state.
