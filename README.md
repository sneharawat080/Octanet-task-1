# Octanet-task-1

## README

### Project Overview

This project uses Three.js to create a dynamic 3D city scene. The project consists of three main files:

- `index.html`
- `style.css`
- `script.js`

### File Descriptions

1. **index.html**: This is the main HTML file that sets up the structure of the webpage. It includes the necessary HTML elements and links to the external CSS and JavaScript files.

2. **style.css**: This CSS file styles the webpage. It ensures the elements are positioned correctly and gives the page a clean and modern look.

3. **script.js**: This JavaScript file contains all the logic for rendering the 3D scene using Three.js. It includes creating the renderer, camera, scene, and various objects within the scene. It also handles animations, lighting, and user interactions.

### Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**: Download or clone the repository to your local machine.

2. **Open index.html**: Open the `index.html` file in your preferred web browser. This will load the webpage and execute the Three.js script.

3. **Explore the scene**: Interact with the scene using your mouse or touch inputs. The scene includes various objects and animations that you can explore.

### Dependencies

This project relies on the following external libraries:

- **Three.js**: A JavaScript library used to create and display animated 3D computer graphics in a web browser using WebGL.
- **TweenMax**: A JavaScript library for tweening and animating HTML5 and JavaScript properties.

### Key Features

1. **Responsive Renderer**: The renderer adjusts its size based on the window size and updates the camera's aspect ratio and projection matrix accordingly.

2. **Fog Background**: The scene includes a skybox texture for the background, creating a foggy atmosphere.

3. **Random City Generation**: The city is generated using randomly positioned and scaled cubes, simulating buildings.

4. **Lighting and Shadows**: The scene includes various types of lighting (ambient, spot, and point lights) and enables shadow mapping for a more realistic look.

5. **User Interaction**: Users can interact with the scene using mouse and touch events to change the camera position and scene rotation.

### Customization

You can customize various aspects of the scene by modifying the `script.js` file. For example:

- **Building Colors**: Change the colors of the buildings by modifying the `setTintColor` function.
- **Lighting Parameters**: Adjust the lighting intensity, position, and type by changing the light variables and their properties.
- **City Layout**: Change the number of buildings, their positions, and scales by modifying the `init` function.
