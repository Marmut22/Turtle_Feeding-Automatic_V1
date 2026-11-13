# 🐢 Automatic Turtle Feeder

An Arduino-based automatic feeding system designed for Red-Eared Slider turtles (*Trachemys scripta elegans*).

This project aims to automate scheduled pellet dispensing using an Arduino Uno, an RTC module, and a servo-controlled mechanical dispenser.

## Overview

The Automatic Turtle Feeder is a DIY embedded systems project that combines electronics, mechanical engineering, and 3D printing.

The system is designed to:
- Dispense turtle food automatically according to a scheduled time.
- Use an RTC module for accurate timekeeping.
- Control food dispensing through a servo motor.
- Store feeding status to prevent duplicate feeding after restarts.
- Use a custom-designed 3D-printed enclosure and mounting system.

## Hardware Components

| Component | Purpose |
|---|---|
| Arduino Uno R3 | Main controller |
| DS3231 RTC | Real-time clock |
| MG90S Servo | Mechanical dispenser control |
| 16x2 LCD I2C | Optional status display |
| 5V External Power Supply | Servo power |
| 3D-Printed Enclosure | Mechanical housing |

## Mechanical Design

The enclosure is designed for installation on the edge of an outdoor concrete pond.

Main mechanical modules:

1. Food Hopper – Stores turtle pellets.
2. Rotary Metering Chamber – Controls food dispensing.
3. Servo Mechanism – Drives the dispensing mechanism.
4. Electronics Enclosure – Protects the control system.
5. Adjustable Saddle Mount – Secures the feeder to the pond edge.

The mechanical parts are designed with 3D printing in mind.

## System Architecture

```text
       DS3231 RTC
            |
            v
       Arduino Uno
            |
            v
       Servo Motor
            |
            v
    Food Dispensing
            |
            v
       Turtle Food
```

## Repository Structure

```text
arduino/       Firmware and Arduino code
electronics/   Wiring diagrams and components
mechanical/    3D models and mechanical designs
documentation/ Assembly and testing guides
images/        Project images and diagrams
```

## Development Status

**Current Version: V1.0 – Prototype Development**

- [x] Initial system architecture
- [x] Component selection
- [x] Initial mechanical concept
- [x] Initial Arduino firmware
- [ ] Final rotary dispensing mechanism
- [ ] Final 3D enclosure
- [ ] Electronics assembly
- [ ] Feeding quantity calibration
- [ ] Reliability testing

## Safety Considerations

This project is intended for development and experimental use.

Before actual deployment:
- Verify dispensing quantity using a scale.
- Test the mechanism for pellet jamming.
- Protect electronics from rain and water splashes.
- Keep electrical connections isolated from the pond.
- Ensure feeding schedules and portions are appropriate for the turtle.

The system should not replace regular monitoring of the animal.

## Technologies

- Arduino C/C++
- Arduino Uno
- DS3231 RTC
- Servo Motor Control
- OpenSCAD
- 3D Printing

## License

License information will be added when the project's distribution terms are finalized.

---

**Project:** Automatic Turtle Feeder  
**Platform:** Arduino Uno  
**Target:** Red-Eared Slider Turtle  
**Version:** 1.0
