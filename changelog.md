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

Changing scene background, settings and creating a addObject function that we use to populate scene
Creating a random color material function
Creating a function addSolidGeometry there we pass geometry as a parameter and create a random colored material and add to scene
Copied code from documentation to have all elements...
Added Font 3D with FontLoader

### Step 7 Scenegraph

1. Creating Sun,Earth and Moon scene...
   Setting camera settings and rotation of objects and adding both to the scene...
   But now instead of adding Earthmesh to scene we add it to Sunmesh instead
   Now adding SolarSystem object
   Adding Moon, plus adding Earth and Moon Orbit
   Adding Axes helpers to see well... axes, mentioning lil-gui
   Now that we see that we want to make a grid with both GridHelper and AxisHelper
   Added controls to display these settings added CSS a little bit

2. Bulding a tank scene where it follows and aims at a sphere
   First we create a targetOrbit with rotation and position as well as a elevation and moving up and down...
   Then we create a tank with SplineCurve and positions as well as the turret and its camera
   We have 4 different types of cameras here detached,on turret, near target and above the tank...
   We cycle through them
