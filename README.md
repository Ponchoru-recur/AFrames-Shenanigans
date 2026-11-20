# A-Frame Lecture 1 and Lecture 2 Activities

ITE-18 Application Development and Emerging Technologies

This repository contains my recreation of every activity covered in the A-Frame Lecture 1 and Lecture 2 slides. Each lecture has its own folder, and each activity inside it has its own numbered folder with an `index.html` file and any images or 3D models it need

## Lecture 1 - A-Frame Fundamental

1. Introduction to A-Frame - Building VR on the Web
2. Creating 3D Objects with A-Frame Primitives
3. Positioning Objects in 3D Space with A-Frame
4. Understanding Rotation and Relative Rotation in A-Frame
5. Scaling and Reflecting Entities in A-Frame
6. Enhancing 3D Objects with Textures and Materials in A-Frame
7. Displaying Flat and Curved Images in A-Frame
8. Breaking Primitives into Entities and Components in A-Frame

## Lecture 2 - A-Frame Scenes, Models and Lightings

1. Creating a Custom Ground in A-Frame
2. Customizing the Sky and Virtual Environment in A-Frame
3. Customizing the Camera in A-Frame
4. Loading and Displaying 3D Models in A-Frame
5. Animating 3D Objects in A-Frame V R
6. Adding Lights and Shadows in A-Frame
7. Precision Lighting Using the A-Frame Inspector

## How run

The scenes load textures and 3D models, so they need to be opened through a local web server rather than by double-clicking the HTML file. Each lecture folder has a small `server.js` that only uses Node.js built-in modules, so there is nothing to install.

```
cd "Lecture 1 - A-Frame Fundamentals"
node server.js
```

Then open http://localhost:3000 in the browser. The page lists every activity in that lecture; click one to open its scene. Lecture 2 works the same way from its own folder.

Inside a scene, drag with the mouse to look around and use the W, A, S and D keys to move. In the last Lecture 2 activity, press Ctrl + Alt + I to open the A-Frame Inspector yeyyyyy.
