# AceSweep Project Overview

## Objective

AceSweep is Team Huanglaoban's EIRP 2026/27 project at the University of Nottingham Malaysia. We are designing a small autonomous rover to retrieve stationary tennis balls during practice breaks. It will identify a ball, move sideways to align the intake, feed the ball into a hopper and confirm that it was collected.

## Constraints

The initial tests will use stationary balls in a supervised, marked 3 m × 3 m area. We will first test the roller and drivetrain separately, then integrate camera-based pickup. We plan to request the Arduino UNO Q 4GB loan and will confirm the onboard computing setup after the loan decision.

## Trade-offs

We chose a three-wheel Kiwi drive so the rover can align the intake while keeping its heading. Omni wheels can slip, so we plan to combine encoder odometry with inertial measurements and use camera feedback during the approach. A compliant foam roller and a curved ramp guide the ball into a mesh hopper. An infrared through-beam sensor will confirm pickup.

## Outcome and planned evidence

The project is at the proposal stage. We will measure motor-loop timing, camera detection and range error, pickup success and recovery behaviour. Our targets are at least 18 successful pickups in 20 controlled single-ball trials and at least eight of ten separated balls collected within five minutes in a multi-ball trial. Weekly updates will document design changes, test results and failures as the prototype develops.
