# CARL — Capstan Actuated Robot Locomotion

CARL is a custom **12-DoF quadruped robot** built to explore mechanical design, capstan actuation, embedded systems and legged robot control.

[Project website](https://jkoradi.github.io/CARL-Website/) · [Interactive leg simulation](https://jkoradi.github.io/CARL-Website/kinematics.html)

## Hardware

- Four legs, three actuated degrees of freedom per leg
- Custom capstan transmissions and five-bar linkages
- 12 BLDC motors with Moteus controllers
- Raspberry Pi 4 and mjbots Pi3Hat, using four CAN-FD buses
- Bluetooth Xbox controller for operator input

## Development status

| Component | Status |
| --- | --- |
| Mechanical prototype and motor integration | Implemented |
| Multi-motor automated homing | Tested |
| Analytical 2D leg IK | Developed and single-leg tested |
| Coordinated 3D leg motion | In development |
| Walking gaits | Planned |
| Terrain perception and stair climbing | Planned |

## Repository layout

- [software/](software/) — Python control software (source to be published)
- [hardware/](hardware/) — CAD, electronics, and bill of materials
- [docs/](docs/) — architecture, motor mapping, calibration and setup
- [media/](media/) — photos, diagrams, and demonstrations

## Documentation

- [Control architecture](docs/architecture.md)
- [Motor mapping](docs/motor-mapping.md)
- [Homing and calibration](docs/homing.md)
- [Getting started](docs/getting-started.md)

## Code availability and licensing

The working Raspberry Pi code has **not yet been uploaded**. Hardware-specific configuration and safety settings must be reviewed before publication.

No license has been selected yet; no general reuse permission is granted until a license is added.
