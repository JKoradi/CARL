# Control architecture

```text
Xbox controller (Bluetooth)
          |
          v
Raspberry Pi 4 (Python)
          |
          v
mjbots Pi3Hat
    |     |     |     |
  CAN 1 CAN 2 CAN 3 CAN 4
    |     |     |     |
   Three Moteus-controlled BLDC motors per leg
```

Python coordinates operator input, homing, and motion targets. The Pi3Hat provides four CAN-FD buses and an IMU. The diagram is conceptual, not an electrical schematic.

The motor interface and homing have been tested. Coordinated 3D control and gait generation remain in development.
