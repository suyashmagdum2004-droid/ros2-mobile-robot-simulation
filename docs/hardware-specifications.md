# Hardware Specifications

## Purpose

This document records the intended physical characteristics and hardware interfaces of the mobile robot. The current repository is focused on simulation. Values that have not been selected or measured are deliberately marked as **TBD** rather than estimated.

## Robot concept

The target platform is a two-wheel differential-drive mobile robot with:
- Two independently driven wheels.
- A supporting caster or equivalent balance support.
- A rigid chassis.
- A forward-facing 2D LiDAR mounting position.
- An onboard compute platform capable of running ROS 2.

## Provisional specification

| Subsystem | Planned specification | Status |
|---|---|---|
| Drive configuration | Differential drive | Planned |
| Drive motors | Two independently controlled motors | Selection TBD |
| Wheel encoders | Feedback for wheel rotation / odometry | Selection TBD |
| Chassis | Rigid mobile base | Dimensions TBD |
| Support | Caster wheel or equivalent | Selection TBD |
| LiDAR | 2D scanning LiDAR | Model TBD |
| Main computer | ROS 2 compatible computer | Model TBD |
| Motor driver | Compatible with selected motors and controller | Selection TBD |
| Power system | Battery and regulated power rails | Voltage and capacity TBD |

## Measurements to record

The following values must be measured or selected before creating a hardware-specific robot model:

- Chassis length, width, and height.
- Wheel radius and wheel separation.
- Wheel and chassis mass.
- Motor rated voltage, speed, and torque.
- Encoder resolution.
- LiDAR mounting height and orientation.
- Battery voltage and capacity.
- Total robot mass and expected operating time.

## Simulation assumptions

Until physical hardware is finalized, the simulation will use clearly documented provisional dimensions and parameters. Simulation values must not be presented as measured hardware specifications.

## Hardware integration checklist

- [ ] Confirm motor and motor-driver specifications.
- [ ] Confirm encoder type and resolution.
- [ ] Measure wheel radius and wheel separation.
- [ ] Select and document the LiDAR model.
- [ ] Define the power distribution and protection requirements.
- [ ] Measure the completed chassis.
- [ ] Compare simulated motion with physical measurements, if a physical prototype is built.

## Safety notes

Any future physical implementation must include appropriate power protection, secure wiring, a reliable motor stop mechanism, and safe testing practices. Simulation success alone does not establish that a physical robot is safe to operate.
