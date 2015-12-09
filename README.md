#OOP JS Project
===============================

This is an OOP JS project, with 3 main JS files.

###resources.js
The resources.js is simply an image loading utility. It eases the process of loading image files so that they can be used within the game. It also includes a simple "caching" layer so it will reuse cached images if you attempt to load the same image multiple times.

###engine.js
This file provides the game loop functionality (update entities and render), draws the initial game board on the screen, and then calls the update and render methods on the player and enemy objects (defined in app.js).

This engine is available globally via the Engine variable and it also makes the canvas' context (ctx) object globally available to make writing app.js a little simpler to work with.

###app.js
This is where the enemy and player objects are created. These objects have an update and render function that are called in the game engine. 

The file also adds an eventListener for any keyDown event, and then filters these to see if they are up, down, left, or right




