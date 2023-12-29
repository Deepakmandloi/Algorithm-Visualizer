# Algorithm-Visualizer
A web application to visualize various pathfinding algorithms on a Grid

Check the website here :- https://pathfinding-visualizer-iitg.herokuapp.com/

## Screenshots
<img src="./p2.png" width="800">
<img src="./p1.png" width="800">

## Installation
### Cloning the repository:
Clone the repository using git clone https://github.com/hsureka/pathfinding-visualizer.git
### Installing dependencies:
Run `npm install`
### Starting the server:
Run `npm start`.
Open http://localhost:3000 to view it in the browser.

## Features
### Positioning the start and end node
You can move the start and end node to which ever cell you want by dragging and dropping

### Adding walls
Firstly, make sure you the the rightmost yellow button as Toggle (Node Type=Wall)
You can add walls to which ever cells you want by clicking the mouse and dragging it and the same goes for removing them
You can also toggle between wall cell and normal cell

### Adding Weighted Nodes
Firstly, make sure you the the rightmost yellow button as Toggle (Node Type=Weighted(6))
You can add weighted node to which ever cells you want by clicking the mouse and dragging it and the same goes for removing them
You can also toggle between wall cell and normal cell

### Auto calculation of shortest path
The shortest path is calcuted on itself on moving the start or end node without having to press the calculate shortest path button.

### Visualization of Path
Visualize the generated path by clicking the Visualize Path Button

### Clear Grid
Clears the grid and removes all the weighted node and walls

### Clear Visualization
Clears the visualization of the algorithm and make every visited node and shortest path node as unvisited node.

For example these are the visualized paths for the A-Star and Dijkstra Algorithm

### After visualization
After visualization you can reposition start and end node as you want and add and delete walls as you wish and visualize using any algorithm again without reloading the webpage

## Developers
### This Project was built by

- [Deepak Mandloi](https://github.com/Deepakmandlo)
- [Kartik Verma](https://github.com/kartikverma044)
