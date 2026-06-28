# USB HID Productivity Controller

This project is a custom-designed USB Human Interface Device (HID) intended to improve productivity by providing programmable physical controls for common computer shortcuts, macros, and application-specific commands. Inspired by commercial workflow controllers, the device combines mechanical design, embedded systems, and electronics into a compact and ergonomic desktop peripheral.

The project was undertaken to develop practical skills across multiple engineering disciplines, including CAD, embedded programming, electronics integration, rapid prototyping, and iterative product development. The final design aims to provide an intuitive and customizable interface while maintaining a clean, manufacturable, and serviceable construction.

## Objectives
- Design a fully custom USB HID controller from the ground up.
- Create an ergonomic layout that minimizes hand movement during repetitive tasks.
- Develop firmware capable of emulating standard USB keyboard and multimedia inputs.
- Design an enclosure suitable for additive manufacturing.
- Produce a modular design that can be easily assembled, maintained, and modified.

This project involved:

- Designing the enclosure and internal mechanisms in Autodesk Fusion 
- Selecting and integrating switches, rotary encoders, and USB hardware
- Developing Arduino firmware implementing the USB HID protocol
- Iteratively refining the ergonomic layout through prototyping
- Manufacturing and assembling the final device using 3D printed components
  
## Features
- Custom USB HID functionality, compatibility tested with Windows and IOS
- Programmable buttons and encoders for keyboard shortcuts and macros.
- Ergonomic enclosure designed using Autodesk Fusion.
- Modular internal construction for simplified assembly and maintenance.
- 3D printable housing optimised for desktop manufacturing.

## Engineering Design Process
### 1. Requirements 
   
The project began by identifying the primary requirements for a productivity controller:

- Comfortable one-handed operation.
- Reliable USB communication.
- Compact desktop footprint.
- Easy assembly and maintenance.

Existing commercial workflow controllers were analysed to identify common design features and potential improvements.

### 2. Concept Development
   
Multiple enclosure concepts and control layouts were explored through sketches and CAD modelling. Particular attention was given to:

- and ergonomics.
- Button accessibility.
- Internal packaging constraints.
- Manufacturing and assembly simplicity.

Several iterations were evaluated before selecting the final configuration.

### 3. Mechanical Design

The enclosure and internal components were designed using Fusion 360.

Mechanical considerations included:

- Structural rigidity.
- Printability without excessive support material.
- Component mounting features.
- Tolerances and additive manufacturing constraints. 
- Ease of assembly and disassembly.
- Aesthetic appearance.

### 4. Firmware Development

Firmware was developed in Arduino IDE with some assistance from AI and online repositories to interpret user inputs and transmit standard USB HID commands to the connected computer.

Software functionality includes:

- Button state detection.
- Input debouncing.
- Rotary encoder processing.
- USB HID communication.
- Configurable key mapping.

The firmware was written with modularity in mind to simplify future feature additions.

### 5. Prototyping and Testing
Successive prototypes were produced using additive manufacturing to validate:

- Ergonomics.
- Assembly process. 
- Structural integrity.
- Component fit.
- Input responsiveness.
- Overall usability.

Feedback from testing informed several design revisions prior to the current iteration.

## Skills Demonstrated

- Mechanical Design
- CAD (Fusion 360)
- Product Design
- Design Iteration
- Ergonomics
- USB HID Development
- Electronics Prototyping
- Soldering and Electronics manufacutring 
- Rapid Prototyping
- 3D Printing

## Future Improvement

Potential future developments include:

- custom PCB replacing point-to-point wiring.
- Wireless Bluetooth connectivity.
- RGB lighting with user-configurable effects.
- OLED status display.
- Battery powered to reduce power consumption of host device. 
- Companion desktop configuration software.
- Swappable control modules.
