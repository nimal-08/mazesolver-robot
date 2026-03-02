# Maze Solver Robot with Environmental Sensing – e-Yantra Competition

## Overview
This project was developed as part of the e-Yantra Robotics Competition.  
The robot autonomously navigates through a maze, explores all dead ends, and records environmental parameters such as temperature, humidity, and soil moisture at each dead-end location.

The objective was to demonstrate autonomous navigation combined with real-world sensing.

## Key Features
- Autonomous maze exploration algorithm
- Detection and traversal of all dead ends
- Environmental sensing at each deadend node
- Real-time control and navigation logic implemented using FPGA tools

## My Role
- Designed and implemented navigation logic
- Worked on sensor interfacing and data acquisition
- Developed control logic using Quartus
- Assisted in debugging navigation and sensor integration issues

## Technologies Used
- FPGA development using Quartus
- Embedded logic design
- Environmental sensors (temperature, humidity, moisture)
- Motor control and navigation circuitry

## Challenges Faced
The primary challenge was tuning the motor driver and motion control to achieve precise turns inside the maze.  
Even small variations in motor speed or wheel response caused deviation from intended paths, which affected navigation accuracy.
To solve this, multiple rounds of calibration and testing were performed to balance motor output and improve turning precision.
The navigation algorithm itself was implemented successfully, and once motion control was stabilized, the robot was able to execute the maze-solving logic reliably along with sensor data collection.

## Outcome
The robot successfully explored the maze, detected all dead ends, and recorded environmental readings at each node.  
This project strengthened my understanding of hardware logic design, autonomous navigation, and real-time system integration.
