# VirtualRobotLib
 2D Robot Simulation Library

## 1.0 Library System Design
The library has several things to accomplish, including:
1. Give a clean and straight-forward API to control robot.
2. Use a seperate thread to use Physics to simulate real world situation.
3. Give a clean and straight-forward API to handle draw call requests from simulator GUI.

Note that the VirtualRobot Library does not handle the actual drawing of simulated robots, instead it only handles the simulation of physics around the robot and provides a DarbotsBotLibCore-based API to end users.   
Simulated Physical World result can be accessed via an API for GUI renderer programs to communite with this library.   