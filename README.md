# robot-kinematics-visualizer

# 3D Kinematics Frame Simulator

An interactive 3D simulator for learning robot kinematics and homogeneous transformations using HTML, CSS, JavaScript, and Three.js.

## Features

- World Frame {W}
- Fixed Local Base Frame {F}
- Dynamic Current Frame {P}
- Translation and Rotation Inputs
- World, Fixed, and Local Transformation Modes
- 4×4 Homogeneous Transformation Matrix Display
- Rotation Matrix and Position Vector
- Smooth Animation
- Orbit Controls
- Export Matrix to Clipboard

## Transformation Modes

### World Mode
T_new = T_input × T_current

### Fixed Local Base Mode
T_new = T_F × T_input × T_F⁻¹ × T_current

### Current Local Mode
T_new = T_current × T_input



## Educational Purpose

This simulator helps students understand:
- Coordinate frames
- Pre-multiplication vs post-multiplication
- Homogeneous transformations
- Robot kinematics

## License

MIT License
