
# Command Line FPV

This application is a simple yet educational Command Line Fist Person Viewer Engine, inspired by classic games like Wolfenstein. It uses console graphics to simulate a first-person view within a maze-like environment

## Requirements

* Operating System: Windows
* Console Dimensions: 120 Columns by 40 Rows
* Adjust console properties to set dimensions to 120x40. Use a small font like "Consolas" at size 16 for optimal display.

## Controls

* A: Turn Left
* D: Turn Right
* W: Walk Forwards
* S: Walk Backwards


## Application

1. Compile: Compile the provided C++ code using your preferred C++ compiler (e.g., Visual Studio, g++).

2. Setup Console:

* Right-click on the console title bar and select "Properties".
* Set the console dimensions to 120 Columns by 40 Rows and choose a small font like "Consolas" at size 16.

3. Run: Execute the compiled executable.

## Game Play

![FPV](assets/FPV.gif)

* Movement: Use W to move forwards, S to move backwards, A to turn left, and D to turn right.
* Environment: The world is represented by a grid of walls (#) and open spaces (.).
* Graphics: The engine uses ray-casting to render a pseudo-3D view of the environment in the console.
## Features and Limitations
### Features:
* Real-time ray-casting to render the environment.
* Simple collision detection with walls.
* Basic shading based on distance from the player.
### Limitations:
* Console-based graphics are limited in fidelity compared to modern 3D games.
* Movement and rendering might not be as smooth due to console-based nature.

## Future Enhancements
### Potential Improvements:
* Implement bullets and shooting mechanics.
* Add enemies and combat mechanics.
* Optimize ray-tracing algorithms for better performance.
* Enhance graphical fidelity and environmental interactions.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

* Fork the repository.
* Create a new branch (git checkout -b feature-branch).
* Commit your changes (git commit -am 'Add new feature').
* Push to the branch (git push origin feature-branch).
* Open a Pull Request.

## License
This project is licensed under the [MIT License](https://www.mit.edu/~amini/LICENSE.md) 


