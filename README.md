Pro Model Viewer v1.1.21
A high-performance, web-based 3D asset inspector for rapid visualization and technical analysis.

Pro Model Viewer is a streamlined tool designed for 3D artists and developers. It allows for instant previewing of 3D models directly in the browser without the need for heavy installation. It features industrial-grade transformation tools, animation support, and smart material linking.

🚀 Key Features
Multi-Format Support: Import GLB, GLTF, FBX, and OBJ files via drag-and-drop.

Smart Material Linking: Automatically links OBJ geometry with MTL libraries and textures when dropped together.

Precision Transforms: * Manual entry via number fields.

Scrubbable Labels: Click and drag X/Y/Z labels for intuitive adjustments.

Uniform Scaling: Toggleable lock for proportional scaling.

Professional Viewport:

Locked horizon (Yaw/Tilt) to prevent camera banking.

Double-click to focus on specific objects.

Toggleable XZ Ground Plane and 3D Axis Gizmos.

Animation Engine: Full playback controls for skeletal animations with Linear/Discrete interpolation switching.

Object Inspection: Toggle wireframe, unlit materials, and visualize skeletons for rigged models.

🛠 Usage Instructions
Navigation
Right-Click + Drag: Rotate/Tilt camera view.

WASD: Move the camera position (active during Right-Click).

Scroll Wheel: Zoom in/out or scale selected object (depending on context).

Double-Click: Automatically lerp the camera to center the clicked object.

Transforming Objects
Select an object from the Scene Outliner or click it in the viewport.

Use the Dashboard inputs to modify position, rotation, or scale.

Pro Tip: Hold Shift while dragging the X/Y/Z labels for high-precision value scrubbing.

Loading OBJ + MTL
To see textures on OBJ models, select the .obj, .mtl, and all associated .jpg/.png files simultaneously and drag them into the viewport.

💻 Local Setup (Non-Node.js)
Since this is a single-file application, you can run it locally without installing Node.js:

Python: Run python -m http.server 8000 in the project folder and visit localhost:8000.

VS Code: Use the Live Server extension.

Shortcut Method: Launch Chrome with the --allow-file-access-from-files flag to load textures directly from your hard drive.

📄 License & Credits
Author
Robin Huybrechts

License
This project is released under the MIT License. You are free to use, modify, and distribute this software, provided that the original copyright notice and author credit remain intact.

Disclaimer
This code was generated partially with the use of AI. The author is not responsible for any issues, data loss, or hardware problems caused to the end user by the use of this software. Use at your own risk.

📈 Version History
v1.1.21: Added author credits and legal disclaimer to instructions overlay.

v1.1.20: Implemented full-screen instructions overlay with contextual help cards.

v1.1.18: Fixed dashboard layout overflow and improved mobile-responsive input widths.

v1.1.17: Integrated MTLLoader for complex OBJ material support.

v1.1.16: Optimized camera initialization to prevent initial horizon tilt.

v1.1.0 - v1.1.15: Initial development of core Three.js pipeline, animation support, and transform tools.
