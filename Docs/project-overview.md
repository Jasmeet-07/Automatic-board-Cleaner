# Project Overview
## Automatic Whiteboard Cleaning System Using RF Remote and Relay Logic

---

## 1. Introduction

The Automatic Whiteboard Cleaning System Using RF Remote and Relay Logic is a hardware-based electromechanical innovation designed to automate the whiteboard cleaning process.

The invention is intended for classrooms, educational institutions, offices, and conference halls where manual whiteboard cleaning can cause unnecessary delays.

The system uses wireless RF remote control, DC gear motors, relay logic, and mechanical limit switches to perform automatic cleaning without requiring Arduino, microcontrollers, or software programming.

## 2. Problem Statement

Traditional whiteboard cleaning requires manual effort and takes time between lectures, meetings, and presentations.

Existing automated cleaning approaches may use programmable controllers and complex electronic systems, increasing implementation costs and maintenance requirements.

This project introduces an electromechanical alternative that uses RF remote control and relay-based automation to simplify the cleaning process.

## 3. Objectives

The main objectives of this invention are:

- To develop a low-cost, hardware-based automatic whiteboard cleaner.
- To reduce manual cleaning effort in classrooms.
- To enable wireless operation using RF signals.
- To implement automatic motor direction control.
- To provide easy installation and minimal maintenance.
- To improve classroom and institutional efficiency.

## 4. System Description

The system consists of a motorized eraser assembly mounted on a linear track or belt-driven mechanism.

When the user activates the system through an RF remote, the DC gear motor moves the eraser pad across the whiteboard surface.

A dual-relay module configured as an H-bridge controls the forward and reverse rotation of the motor.

Two SPDT limit switches are positioned at opposite ends of the whiteboard to detect movement boundaries and control automatic direction reversal.

The cleaning cycle continues until the eraser returns to its home position, where the designated limit switch stops the motor.

## 5. Main Hardware Components

| Component | Description |
|---|---|
| RF Remote Control | Activates the cleaning operation wirelessly. |
| RF Receiver | Receives the remote control signal. |
| DC Gear Motor | Drives the eraser mechanism. |
| Dual Relay Module | Controls forward and reverse motor operation. |
| SPDT Limit Switches | Detect the end positions of the cleaning mechanism. |
| Timing Belt and Pulleys | Transfer mechanical motion. |
| Eraser Pad | Performs the whiteboard cleaning operation. |
| 12V DC Adapter | Supplies electrical power. |
| Mounting Frame | Supports the mechanical assembly. |

## 6. Working Methodology

The system operates through the following sequence:

**Step 1 – Activation**

The user presses the RF remote button to activate the cleaning system.

**Step 2 – Motor Operation**

The RF receiver activates the relay control mechanism, allowing the DC gear motor to move the eraser assembly.

**Step 3 – Linear Movement**

The belt and pulley arrangement transfers motor movement to the eraser pad, allowing it to travel across the whiteboard.

**Step 4 – Boundary Detection**

When the eraser reaches the opposite end, the corresponding SPDT limit switch is triggered.

**Step 5 – Automatic Reversal**

The relay-based H-bridge changes the motor polarity, reversing the direction of movement.

**Step 6 – Completion**

The eraser returns to its home position, where the designated limit switch stops the motor and completes the cleaning cycle.

## 7. Technical Specifications

| Parameter | Specification |
|---|---|
| RF Frequency | 433 MHz |
| Power Supply | 12V DC, 2A |
| Motor Type | DC Gear Motor |
| Motor Control | Dual Relay H-Bridge |
| Limit Switch Type | SPDT Mechanical |
| Movement Mechanism | Linear Track / Timing Belt |
| Cleaning Material | Felt / Rubber |
| Control Technology | Electromechanical Relay Logic |
| Microcontroller | Not Required |
| Software Programming | Not Required |

## 8. Key Innovation

The key innovation is the implementation of automatic whiteboard cleaning through a purely electromechanical control system.

Instead of depending on Arduino, microcontrollers, or embedded software, the system uses:

- RF-based wireless activation.
- Relay-based motor direction control.
- Mechanical limit-switch feedback.
- Automatic movement and direction reversal.

This approach provides an alternative to programmable whiteboard cleaning systems.

## 9. Applications

The proposed invention can be used in:

- Schools and colleges.
- Universities and classrooms.
- Corporate meeting rooms.
- Coaching institutes.
- Conference halls.
- Educational training centres.

## 10. Future Scope

Possible future development areas include:

- Compatibility with different whiteboard dimensions.
- Improved mechanical design and stability.
- Enhanced cleaning-pad materials.
- Improved power efficiency.
- Commercial deployment in educational institutions.

These are potential development directions, not features claimed to have already been implemented.

## 11. Patent Information

| Field | Details |
|---|---|
| Invention Title | Automatic Whiteboard Cleaning System Using RF Remote and Relay Logic |
| Applicant | Chandigarh University |
| Specification Type | Form 2 – Complete Specification |
| Specification Date | 22 November 2025 |
| Project Mentor | Dr. Manish Sharma |

*Refer to official patent records for verified inventorship, application status, and ownership.*

## 12. Conclusion

The Automatic Whiteboard Cleaning System demonstrates how simple electromechanical components can be combined to automate a common task in educational and professional environments.

By integrating RF remote control, DC gear motors, relay logic, and limit switches, the invention provides an alternative approach to automatic whiteboard cleaning without requiring software programming.

The project focuses on simplicity, automation, cost-effectiveness, and practical engineering innovation.

---

**Project:** Automatic Whiteboard Cleaning System Using RF Remote and Relay Logic

**Institution:** Chandigarh University

**Project Mentor:** Dr. Manish Sharma
