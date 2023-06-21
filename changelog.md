Documentation

### Step 1

### https://threejs.org/docs/index.html#manual/en/introduction/Installation

Created index.html and main.js
Install three.js and vite with npm install --save three npm install --save-dev vite and npx vite

### For production later

Run npx vite build - will create dist/ folder...

### Step 2 - Create a scene with green rotating cube

### https://threejs.org/docs/#manual/en/introduction/Creating-a-scene

We are setting up Camera, Scene and Renderer...
We are adding cude to the mix
We are rendering the scene and animating the cube

### Step 3 - Creating 2 blue lines connecting making an upwords arrow

### https://threejs.org/docs/#manual/en/introduction/Drawing-lines

We are adding lines and coordinates

### Step 4 - FUNDAMENTALS

### https://threejs.org/manual/#en/fundamentals

Adding a canvas in index.html and editing index.js with main function where we define renderer
Then we add parameters and camera into the main function
Editing camera position z coordinate back a little bit so what we can see
Making a scene and Box Geometry or Cube and define Mesh as Geometry and Material of a object are defined...
Then we add cube to the scene and we render the scene with the camera
We delete the main function declaration since we do not need it and just run the script...
Now we animate the cube with rotation and requestAnimationFrame
We now added light and changed material to see 3D clearer
Now we add 2 more cube with makeInstance function and we rotate them as well plus refactoring

### Step 5 - Responsive Design

### https://threejs.org/manual/#en/responsive

Changing css in index.html file
Fixing so that the resolution is perfect with client window size
Adding resizeDisplaySize function in order to set the canvas resolution
Refactoring with HD-DPI display in focus

### Step 6 - Looking at PRIMITIVES

### https://threejs.org/manual/#en/primitives
