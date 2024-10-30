# 🌟 Robotic Arm and Wheeled Base Simulation

Welcome to my first project utilizing **URDF**, **RViz**, and **Gazebo**! This repository showcases a robotic arm and a wheeled robot base model designed for simulation within the ROS ecosystem.

## 🎯 Project Overview

This project aims to demonstrate my understanding of robotic simulation by creating a simple robotic arm and a mobile base. By integrating URDF models with Gazebo, I gained hands-on experience in simulating robotic movements and visualizing them in RViz.

## 🛠️ Skills Developed

Throughout this project, I have sharpened several key skills:

- **URDF Modeling**: Learned to create and manipulate URDF files to define robot components, including links and joints.
- **XACRO**: Utilized XACRO to simplify the URDF creation process by defining reusable properties and macros, making the models more modular and easier to manage.
- **Simulation with Gazebo**: Explored the Gazebo simulator for realistic physics and visual representation of robot models, allowing for dynamic interactions and testing in a virtual environment.
- **Visualization in RViz**: Familiarized myself with RViz to visualize the robot's structure and movements, aiding in debugging and development.
- **ROS Integration**: Gained experience in setting up and configuring ROS plugins to publish joint states and control the robot's movements.

## 🤖 Project Components

### 1. Robotic Arm Model

- **Structure**: The arm consists of three main components: 
  - **Arm Base**: A stable base that anchors the arm.
  - **Forearm**: A cylindrical link that rotates relative to the arm base.
  - **Hand**: A tool for manipulation, attached to the end of the forearm.

- **Joints**: The arm features two revolute joints, allowing for flexible movement and interaction with objects.

### 2. Wheeled Robot Base

- **Design**: The base includes:
  - **Main Body**: Provides stability and houses all components.
  - **Drive Wheels**: Two continuous wheels that enable movement.
  - **Caster Wheel**: A supporting wheel to maintain balance during motion.

- **Control**: Integrated Gazebo plugins for differential drive control and odometry tracking enhance the robot's maneuverability.

### 3. Camera Sensor

- **Integration**: A camera sensor has been added to the base link to enable visual perception of the robot's environment.
- **Configuration**: The camera's position and orientation are defined in the URDF model, allowing it to capture the desired field of view.

## 🚀 Why This Project?

This project serves multiple purposes:

1. **Learning Experience**: As a computer science student with a passion for robotics, I aimed to deepen my understanding of robotic simulation and control. This project is a foundational step in my journey to becoming proficient in ROS and robotics.

2. **Hands-On Application**: Working with XACRO, URDF, RViz, and Gazebo allowed me to apply theoretical knowledge in a practical context, bridging the gap between classroom learning and real-world applications.

3. **Future Endeavors**: This project sets the stage for more complex robotics projects, including obstacle avoidance algorithms, sensor integration, and advanced control systems.

