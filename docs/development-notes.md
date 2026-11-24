# Development Notes

This document records the development plan, decisions, and progress for the ROS 2 mobile robot simulation.

## Development approach

The project will be developed incrementally. Each subsystem will be documented and tested before it is treated as complete.

## Milestones

### Milestone 1 — Repository and environment
- [x] Create the project repository.
- [x] Add the project overview.
- [x] Document the initial development roadmap.
- [ ] Record the exact Ubuntu and ROS 2 environment.
- [ ] Create and document the ROS 2 workspace structure.

### Milestone 2 — Robot description
- [ ] Define the robot's base and wheel links.
- [ ] Define joints and wheel geometry.
- [ ] Add the LiDAR mounting frame.
- [ ] Validate the robot description in RViz2.

### Milestone 3 — Simulation
- [ ] Prepare the simulation launch configuration.
- [ ] Add a simple test world.
- [ ] Spawn the robot in the simulator.
- [ ] Verify differential-drive motion.

### Milestone 4 — Sensors and visualization
- [ ] Integrate simulated LiDAR.
- [ ] Verify the scan topic and frame.
- [ ] Verify odometry output.
- [ ] Inspect TF relationships in RViz2.

### Milestone 5 — Mapping and navigation
- [ ] Configure SLAM Toolbox.
- [ ] Create and save a test map.
- [ ] Configure localization.
- [ ] Configure Nav2 and test goal navigation.
- [ ] Test obstacle avoidance and safe stopping.

## Engineering notes

- Keep simulation configuration separate from robot description files.
- Use clear frame names and document the TF tree.
- Record important ROS 2 topics, message types, and expected frame IDs.
- Keep parameters in configuration files instead of scattering constants through code.
- Test each subsystem independently before integrating it with the full navigation stack.

## Progress log

| Date | Update |
|---|---|
| 2026-11-24 | Created the repository overview and initial development documentation. |

## Status policy

A task is marked complete only after its implementation has been checked. Planned work must not be presented as a tested feature.
