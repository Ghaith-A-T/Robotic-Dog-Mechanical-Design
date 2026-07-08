# Robotic-Dog-Mechanical-Design
Initial mechanical design of a four-legged robotic dog including 3D model, mechanical specifications

## Project Overview
This project presents the initial mechanical design of a simple quadruped robotic dog. The robot is designed with a rectangular chassis and four legs to provide a stable and lightweight platform for educational robotics applications.

---

## Mechanical Specifications

### Overall Dimensions
- **Body Length:** 40 cm
- **Body Width:** 25 cm
- **Body Height:** 25 cm
- **Number of Legs:** 4

### Chassis
- **Structure:** Rectangular box frame
- **Material:** PLA (3D Printed) or Lightweight Aluminum
- **Wall Thickness:** 3–5 mm

### Leg Design
Each leg consists of:
- Upper leg
- Lower leg
- Foot support

Approximate leg length: **12 cm**

### Joints and Degrees of Freedom
- Hip Joints: 4
- Knee Joints: 4
- Total Joints: 8
- Degrees of Freedom (DOF): 8

### Servo Motors
**Recommended Motor:** MG996R Servo Motor

Specifications:
- Operating Voltage: 4.8–7.2 V
- Stall Torque: 9–11 kg·cm
- Rotation Angle: 180°
- Number of Motors: 8

### Estimated Weight
| Component | Estimated Weight |
|-----------|-----------------:|
| Chassis | 1.0 kg |
| Servo Motors (8) | 0.44 kg |
| Battery | 0.35 kg |
| Controller & Wiring | 0.20 kg |
| **Total** | **≈ 2.0 kg** |

### Torque Requirement
Estimated required torque per leg joint:

**≈ 0.6 N·m**

The selected MG996R servo motor provides sufficient torque for the robot's movement.

### Center of Gravity
The center of gravity is located near the center of the chassis by placing the battery and controller in the middle of the body. This improves balance and walking stability.

### Walking Method
The robot uses the **Crawl Gait** walking pattern.

Movement sequence:
1. Front Right
2. Rear Left
3. Front Left
4. Rear Right

### Materials
- Chassis: PLA / Aluminum
- Legs: PLA
- Servo Brackets: PLA or Aluminum
- Fasteners: M3 Steel Screws
- Feet: Rubber Pads

### Expected Mechanical Challenges
- High power consumption
- Servo overheating
- Chassis vibration
- Leg slippage on smooth surfaces
- Increased joint stress under heavy loads
---
## Software
- CAD Design: Tinkercad
- 3D Model Format: STL

---

## Author
**Ghaith**
