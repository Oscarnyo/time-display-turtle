# time-display-turtle

## Overview
This repository contains the ROS (Robot Operating System) code for a project involving autonomous mobile robotics. The primary functionality includes controlling turtles in the `turtlesim` package to display the current time in a creative and interactive manner.

## Features
- **Time Display with Turtles**: Utilizes turtlesim turtles to draw numbers representing the current time.
- **Dynamic Time Update**: The display updates in real-time to reflect the current time in hours, minutes, and seconds.

## Prerequisites
- ROS (Robot Operating System)
- turtlesim package (usually comes with standard ROS installation)

## Installation
1. Clone the repository into your ROS workspace.
2. Build the package using ROS build tools (e.g., `catkin_make`).

## Usage
To run the time display:
1. Launch the ROS master: `roscore`
2. Run the `main.launch` file: `roslaunch [package_name] main.launch`

## File Description
- `main_draw.txt`: Core script to control turtle movements and display time.
- `main.launch`: Launch file to initialize the ROS nodes.
- `turtle_time_listener.txt`: Additional script for turtle time listening functionalities.

## Contributing
Feel free to fork this repository and submit pull requests to contribute to this project.

## Acknowledgements
Special thanks to Soon Wei, Hao Jie, and Jun Ting for their guidance and support in this project.
- Soowei: https://github.com/SwS651
- Hao Jie: https://github.com/Mito8888
- Jun Ting: https://github.com/Chen08-16
