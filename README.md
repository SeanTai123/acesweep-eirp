# AceSweep Autonomous Tennis Ball Collector

AceSweep is a proposed rover that collects stationary tennis balls during practice breaks. Three omni wheels let it move sideways to align a foam roller with the ball. The roller feeds the ball into a hopper, and an infrared sensor confirms pickup.

## Team

Huanglaoban · University of Nottingham Malaysia · EIRP 2026/27

- Gan Ching Kang (team lead)
- Ng Anson
- Tai Jia Xuan
- Wong Yan Jie

## Design

A USB camera and OpenCV identify tennis balls. ROS 2 combines wheel odometry and inertial measurements and uses camera feedback to guide the approach. An embedded controller runs the wheel-speed loops, reads the capture sensor and stops the drive if commands go stale.

The first prototype will be tested in a supervised 3 m × 3 m area. The team aims to confirm at least 18 pickups in 20 single-ball trials and collect at least eight of ten separated balls within five minutes in a multi-ball trial.

## Repository

- [Hardware](hardware/) — mechanical design, wiring, electronics and parts
- [Software](software/) — firmware, ROS 2 and drive simulation
- [Documentation](docs/) — project overview, test plans and build logs

The project is at the proposal stage. The performance figures are test targets.
