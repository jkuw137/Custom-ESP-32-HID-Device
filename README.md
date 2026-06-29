# USB HID Productivity Controller

<img width="898" height="723" alt="image" src="https://github.com/user-attachments/assets/6621ffe1-2eb3-4a43-944c-484a462e5497" />

This project is a custom-designed USB Human Interface Device (HID) intended to improve productivity by providing programmable physical controls for common computer shortcuts, macros, and application-specific commands. Inspired by commercial workflow controllers, the device combines mechanical design, embedded systems, and electronics into a compact and ergonomic desktop peripheral.

The project was undertaken to develop practical skills across multiple engineering disciplines, including CAD, embedded programming, electronics integration, rapid prototyping, and iterative product development. The final design aims to provide an intuitive and customizable interface while maintaining a clean, manufacturable, and serviceable construction.

## Objectives
- Design a fully custom USB HID controller from the ground up.
- Create an ergonomic layout that minimizes hand movement during repetitive tasks.
- Develop firmware capable of emulating standard USB keyboard and multimedia inputs.
- Design an enclosure suitable for additive manufacturing.
- Produce a design that can be easily assembled, maintained, and modified.

This project involved:

- Designing the enclosure and internal mechanisms in Autodesk Fusion 
- Selecting and integrating switches, rotary encoders, and USB hardware
- Developing Arduino firmware implementing the USB HID protocol
- Iteratively refining the ergonomic layout through prototyping
- Manufacturing and assembling the final device using 3D printed components
  
## Features
- USB-C HID functionality, compatibility tested with Windows and IOS
- Programmable buttons and encoders for keyboard shortcuts and macros.
- Ergonomic enclosure designed using Autodesk Fusion.
- Modular construction for simplified assembly and maintenance.
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

- Hand ergonomics.
- Button accessibility.
- Internal packaging constraints.
- Manufacturing and assembly limitations.

<img width="2268" height="1853" alt="IMG_1418" src="https://github.com/user-attachments/assets/11e79fac-31e6-4976-b677-c47d7d26af7e" />
Testing various button arrangments to assess comfort and ergonimics.

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

<img width="567" height="1008" alt="IMG_0945" src="https://github.com/user-attachments/assets/206c222a-f66f-4994-a247-7c8c540a0964" />

Initial testing of code and Microcontroller

The firmware was written with modularity in mind to simplify future feature additions.

### 5. Prototyping and Testing
Successive prototypes were produced using additive manufacturing to validate:

- Ergonomics.
- Assembly. 
- Structural integrity.
- Component fit.
- Input responsiveness.
- Overall usability.
  
<br>
<img width="2268" height="2806" alt="IMG_1385" src="https://github.com/user-attachments/assets/0b0eeee0-d923-445b-aa7d-2f989340be25" />
Desoldering and recycling components.
<p></p>
<br>

<img width="2016" height="1134" alt="IMG_1350" src="https://github.com/user-attachments/assets/ef4f1ff9-8b84-42a2-aa91-bbcd653f2048" />
Testing all buttons and encoders as an integrated sysyem.
<p></p>
<br>

<img width="1134" height="1230" alt="IMG_1937" src="https://github.com/user-attachments/assets/bc0c02b7-cdb9-44ea-aef3-db09b73a1955" />
Initial testing of hardware features and assembly such as the buttons and scroll wheel.
<p></p>
<br>

<img width="1134" height="2016" alt="IMG_1995" src="https://github.com/user-attachments/assets/e0393e7e-7827-4bce-859f-145f628f6b75" />
Electronic hardware manufacuring.
<p></p>
<br>

Feedback from testing informed several design revisions prior to the current iteration.

## Final Operational Design

<img width="4284" height="5712" alt="IMG_2355" src="https://github.com/user-attachments/assets/bbc2435f-855a-4b56-b4fd-5f42b3ea6ad2" />
<img width="5712" height="4284" alt="IMG_2357" src="https://github.com/user-attachments/assets/3408ee37-2eaf-44bd-bbc8-b8d3bbc5345b" />
<img width="5712" height="4284" alt="IMG_2358" src="https://github.com/user-attachments/assets/9247dcb9-ce0d-474e-aa8c-1fc15262fb5c" />



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
