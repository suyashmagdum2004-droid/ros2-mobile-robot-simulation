# ROS 2 Mobile Robot Simulation

A learning and development project for building a differential-drive mobile robot in ROS 2 Humble, with simulation, sensor integration, mapping, and autonomous navigation.

## Project goals

- Create a differential-drive robot model using URDF/Xacro.
- Simulate the robot in Gazebo.
- Integrate LiDAR and wheel odometry.
- Visualize the robot and sensor data in RViz2.
- Generate a map using SLAM Toolbox.
- Localize the robot and navigate to goals using Nav2.

## Planned technology stack

- Ubuntu 22.04
- ROS 2 Humble
- Python (rclpy) and C++ (rclcpp), where appropriate
- URDF / Xacro
- Gazebo Classic (initial simulation target)
- RViz2
- SLAM Toolbox
- Nav2

## Planned repository structure

```text
ros2-mobile-robot-simulation/
├── README.md
├── docs/
│   └── development-notes.md
└── src/
    └── my_robot_description/
        ├── CMakeLists.txt
        ├── package.xml
        ├── launch/
        ├── urdf/
        ├── worlds/
        └── rviz/
```

The structure will be expanded as each component is implemented and tested.

## Development status

| Component | Status |
|---|---|
| Project setup and documentation | In progress |
| Differential-drive URDF | Planned |
| Gazebo simulation | Planned |
| LiDAR and odometry | Planned |
| SLAM mapping | Planned |
| Nav2 autonomous navigation | Planned |

## Development environment

The initial target environment is ROS 2 Humble on Ubuntu 22.04. Commands and configuration will be documented as they are tested.

## How to build

Build instructions will be added after the ROS 2 package files and dependencies are committed.

## Notes

This repository documents the development process. Features will be marked complete only after they have been implemented and tested.
