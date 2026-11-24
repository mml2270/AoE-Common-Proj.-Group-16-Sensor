Arduino-based optical and impact slap detection subsystem.
# Slap Detection System
Subsystem is designed to detect player hand entry and physical impact in a two-player Slap Jack-style card game.

## Hardware Components
- 2 infrared (IR) break-beam sensor pairs
- Piezoelectric impact sensor
- Arduino microcontroller
- Breadboard and jumper wires
- Resistors and signal-protection diodes

## System Functionality
Detects Player 1 and Player 2 hand entry using separate IR break-beam sensors.
Detects physical impact using a piezoelectric sensor.
Records event timestamps.
Evaluates which player likely approached first.
Flags potentially simultaneous events as ambiguous.

## Current Development Stage
Initial prototype and sensor testing.

## Future Work
- Calibrate sensor thresholds.
- Test detection accuracy and response time.
- Develop physical sensor mounts.
- Integrate with the main game Arduino code.
