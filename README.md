## WebGL
WebGL (Web Graphics Library) is a JavaScript API for rendering high-performance interactive 3D and 2D graphics within any compatible web browser without the use of plug-ins. WebGL does so by introducing an API that closely conforms to OpenGL ES 2.0 that can be used in HTML <canvas> elements. This conformance makes it possible for the API to take advantage of hardware graphics acceleration provided by the user's device.

## Three.js
Three.js is a cross-browser JavaScript library and application programming interface (API) used to create and display animated 3D computer graphics in a web browser using WebGL. Three.js is a cross-browser JavaScript library and application programming interface (API) used to create and display animated 3D computer graphics in a web browser using WebGL.
- Create 3D Material
- Create 3D Object
- Create 3D Scene 
- Create Light
- Create Camera

### Box
- MeshStandardMaterial
- BoxGeometry
- Position
- Rotation

### Ball
- MeshStandardMaterial
- SphereGeometry
- Position
- Rotation

### Light
- Directional
- Directional Light with White color  
- Position
- Rotation 
- Intensity (0.5 - 2.0)
- Shadow (4096)
- Ambient Light For Realistic Lighting 

### Camera
- Perspective Camera
- Position
 - lookAt function
- Rotation 
- Fov Angle = 60°
- Sight = 1:1000 (near:far)

### Collusion
- distanceTo function
- if distance between two objects < 1.5; change position, change rotation

### Goal Scenario
- Score Table Changes 
- Position of Objects Reset
- Goal Sound





