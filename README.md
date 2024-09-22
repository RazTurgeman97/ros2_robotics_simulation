# ROS2 Robotics Simulation - TF | URDF | RViz | Gazebo

This repository contains all data and materials related to the **ROS2 for Beginners Level 2 - TF | URDF | RViz | Gazebo** course I am currently taking on Udemy.

## Course Overview

This course is designed for ROS2 developers who have learned the basics and want to take the next step towards building and simulating custom robots. It covers topics such as **TF (Transforms)**, **URDF (Unified Robot Description Format)**, **RViz** for visualization, and **Gazebo** for robot simulation.

### Key Topics:
- Understanding what **TF** is and why it’s needed in robotic applications.
- Writing **URDF** files to describe a robot's physical properties, starting with a mobile robot.
- Using **Robot State Publisher** to generate TFs from URDFs.
- Improving and cleaning up URDF files using **Xacro**.
- Simulating robots in **Gazebo** and adding sensors.
- Creating ROS2 packages and XML/Python launch files to streamline the application startup process.
- Hands-on learning with activities and a final project to apply the concepts of building a robotic arm.

## Repository Structure

- **src/**: Contains the ROS2 packages developed throughout the course.
- **launch/**: Includes launch files for starting the various ROS2 nodes and simulations.
- **urdf/**: The URDF and Xacro files used to describe the robots.
- **rviz/**: Configurations for visualizing the robot and transformations in RViz.
- **gazebo/**: Files related to robot simulation in Gazebo.
- **docs/**: Additional notes, resources, and references from the course.

## Why This Course?

Learning ROS2 on your own can be challenging, especially when dealing with more advanced concepts like TF, URDF, and Gazebo. This course is designed to save you time and frustration by providing a structured, step-by-step approach with real-world projects. By the end of the course, you’ll be able to design and simulate custom robots with ROS2.

## What You Will Learn

By following along with this repository and the course, you will:
- Understand and utilize **TF** to track robot links and transformations.
- Build and simulate robots using **URDF** files and **Gazebo**.
- Improve URDF files with **Xacro** to make them more modular and maintainable.
- Control simulated robots using ROS2 and Gazebo plugins.
- Work with **RViz** to visualize robot states and sensor data.
- Learn how to combine multiple robots in the same simulation environment.
- Create comprehensive ROS2 projects with custom robots.

## Requirements

- Basic knowledge of ROS2 (It is recommended to take the "ROS2 for Beginners" course if you're new).
- **Ubuntu** OS installed (dual boot is preferred).
- ROS2 Foxy/Humble setup.
  
## Final Project

The course culminates in a final project where you will:
- Design and simulate a robotic arm from scratch using the concepts learned.
- Combine two robots and simulate their interaction in **Gazebo**.
  
## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ros2_robotics_simulation.git
