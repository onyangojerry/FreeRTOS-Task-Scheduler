```markdown
# ⏱ FreeRTOS Task Scheduler

This repository contains an embedded systems lab project demonstrating real-time task scheduling using [FreeRTOS](https://www.freertos.org/). It is structured around multiple tasks (vP1Task to vP5Task) that showcase concurrent execution, PWM control, debouncing, and more using the MPLAB X IDE and Microchip toolchain.

---

##  Project Structure

```

FreeRTOS-Task-Scheduler/

├── FreeRTOS\_Lab\_Template.X/
└── src/
├── main.c
├── config/
├── debounce/
├── pwm/
├── dummyTask/
├── vP1Task/ to vP5Task/
└── third\_party/

````
# MPLAB X project folder (project configuration, build files)
 # Application source code
 # Entry point and scheduler setup
# Configuration headers and definitions
# Button debouncing logic
# PWM signal generation
 # Idle/test task
# Custom concurrent tasks
# (Optional) External or vendor libraries
---

##  Getting Started

### Prerequisites
- **MPLAB X IDE** (Microchip)
- **XC32 Compiler**
- A supported Microchip board (e.g., PIC32 series)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/onyangojerry/FreeRTOS-Task-Scheduler.git
````

2. **Open Project**

   * Open `FreeRTOS_Lab_Template.X` in MPLAB X IDE.

3. **Build and Flash**

   * Ensure the correct device and debugger are selected.
   * Build the project and flash it to your microcontroller.

---

##  Key Features

*  Preemptive task scheduling with FreeRTOS
*  Modular task structure (`vP1Task` to `vP5Task`)
*  PWM control for output peripherals
*  Debounced input handling
*  Dummy task for baseline testing
*  Clean separation of concerns by module

---

##  License

This project is intended for educational purposes and lab-based exploration of real-time embedded systems.

---

##  Author

**Jerry Onyango**
 Pomona College | Junior CS Student | Embedded Systems & AI Enthusiast
 [LinkedIn](https://www.linkedin.com/in/onyangojerry) | [GitHub](https://github.com/onyangojerry)



