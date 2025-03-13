# This is repo for CMPUT412
Author: Steven Yang, Jiachen Huang  
This repository contains assignments and projects for the Duckietown robotics course — CMPUT 412. The coursework focuses on hands-on experience with ROS (Robot Operating System) and autonomous robot control. You’ll find implementations of robotics algorithms, debugging approaches, and open-source solutions built on the Duckiebot platform.

---

## Code for Ex 1: Duckiebot Assembly and Basic Development

**Repository Links:**  
- [py-env](https://github.com/StevenYang23/py_env)  
- [lib](https://github.com/StevenYang23/lib)  

**Overview:**  
This exercise introduces the basics of operating a Duckiebot and running Python within a Dockerized environment on the Duckiebot machine. The tasks include assembling and testing the Duckiebot, setting up a course website and GitHub repository, and performing initial hardware and software checks. You’ll document your setup with photos and videos (e.g., driving 2 meters straight, lane following demo, calibration screenshots, and a custom “Hello from MY_ROBOT” display).

**Key Deliverables and Learning Points:**
- Building and testing the Duckiebot’s hardware components.
- Running Docker and terminal commands to interact with the robot.
- Performing sensor calibration (camera and motor signals).
- Troubleshooting issues like drift during straight-line driving and lane-following challenges.
- Optional bonus tasks to extend functionality.

**How to Run the Code:**
1. Clone the repository and navigate to the `Ex1/` subfolder
2. Follow the instructions in the accompanying README to set up Docker and run the tutorials.
3. Verify hardware tests and run your demos as instructed.

---

## Code for Ex 2: ROS Development and Kinematics

**Repository Link:**  
- [412DTROS](https://github.com/StevenYang23/412_DTROS)  

**Overview:**  
Exercise 2 focuses on leveraging ROS to control the Duckiebot. Using the DTROS template as a starting point, you develop ROS nodes and packages to:
- Publish and subscribe to topics (including image annotation from the camera).
- Drive the Duckiebot forward/backward and execute rotations.
- Record odometry data using ROS bags and analyze the robot's trajectory.
- Implement LED signaling and navigate a “D”-shaped path using wheel encoder odometry.

**Key Deliverables and Learning Points:**
- Setting up a catkin workspace and creating custom ROS nodes.
- Implementing odometry for differential drive robots.
- Integrating image processing with ROS for real-time feedback.
- Documenting and analyzing the differences between desired and actual robot behavior.
- Managing ROS resources and ensuring all nodes terminate properly after execution.

**How to Run the Code:**
1. Clone the repository and navigate to the `Ex2&3/` subfolder.
2. Follow the instructions in the accompanying README to set up Docker and run the tutorials.
3. Verify hardware tests and run your demos as instructed.
