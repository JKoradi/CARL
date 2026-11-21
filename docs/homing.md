# Homing and calibration

CARL detects mechanical endstops using motor motion and current/torque response.

1. Home abduction/adduction motors **3, 6, 9, 12** simultaneously.
2. Move them to their configured offsets and hold.
3. Home hip and knee motors **2, 1, 5, 4, 7, 8, 10, 11** simultaneously.
4. Move them to their configured offsets and hold.

The staged sequence has been tested. Exact offsets and tuning values are hardware-specific and not published here.

**Safety:** Support the robot, verify joint limits and torque limits, and ensure immediate motor power disconnect is possible. This is documentation, not a ready-to-run procedure.
