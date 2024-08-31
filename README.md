# Traffic Light Interfacing using LPC2148

## Project Overview

This project focuses on the interfacing of a traffic light system using the LPC2148 microcontroller. The project implements the control logic for the traffic light signals and demonstrates the interaction with external hardware components.

## Features

* **Traffic light control logic:** The project incorporates the necessary logic to control the sequence of traffic light signals.
* **LPC2148 microcontroller:** The project utilizes the LPC2148 microcontroller as the core component for implementing the control logic.
* **Hardware interfacing:** The project demonstrates the interfacing of the microcontroller with external hardware components, likely including LEDs for the traffic lights.

## Installation

**Prerequisites:**

* **Microchip MPLAB IDE:** Download and install the MPLAB IDE software from the Microchip website.
* **LPC2148 development board:** Obtain a development board featuring the LPC2148 microcontroller.

**Installation Steps:**

1. Open the `interfacing.pdsprj` project file in MPLAB IDE.
2. Ensure that the LPC2148 device is selected in the MPLAB IDE project settings.
3. Compile the project by selecting "Build" from the "Project" menu.
4. If required, configure the debugging settings to connect to the LPC2148 development board.

## Usage

1. Connect the LPC2148 development board to the traffic light system hardware.
2. Program the LPC2148 microcontroller with the compiled code from the project.
3. Power on the system. The traffic light signals should begin operating according to the implemented control logic.

**Code Example:**

The `interfacingassgn.c` file contains the source code for the traffic light control logic. The code structure is likely to include functions for:

* Initializing the LPC2148 microcontroller.
* Configuring the I/O pins for the traffic light LEDs.
* Implementing the traffic light signal sequence.

**Note:** The specific code structure and implementation details may vary depending on the project's design and the chosen hardware components. Review the `interfacingassgn.c` file for detailed information on the project's code implementation.

**Troubleshooting:**

* Refer to the project documentation (`Report.pdf` and `Presentation PPT.pdf`) for detailed information on the system's design, implementation, and potential troubleshooting steps.
* Consult the Microchip LPC2148 microcontroller datasheet for technical specifications and support resources.
* If encountering issues, review the code for errors and ensure proper hardware connections.
