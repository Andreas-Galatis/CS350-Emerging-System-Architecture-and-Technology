# CS350-Emerging-System-Architecture-and-Technology

**Thermostat Project**

**Summarize the project and what problem it was solving.**

The project involved writing code for a thermostat protototype that uses the TMP006 temperature sensor on a TI CC3220S microcontroller to read the room temperature (via I2C), an LED to indicate the output to the thermostat where LED on = heat on (via GPIO), two buttons to increase and decrease the set temperature (via GPIO interrupt), and the UART to simulate the data being sent to the server. We had to:

1. Create code that initializes the timer and uses it to drive specified actions. This involves two steps, both the initializing of the timer and then its use in running an action.
2. Create code that uses interrupt to detect button presses. This involves two steps, both the detection of the button presses and then using the result to run an action.
3. Create code to initialize the I2C peripheral and use it to read the temperature sensor. This code must both initialize the I2C peripheral and then read the temperature sensor correctly.
4. Create code to initialize the GPIO peripheral and use it. Remember that the GPIO is involved in indicating the output of the temperature via LED and setting the temperature with two different buttons (one to increase and one to decrease temperature).
5. Create code to initialize the UART peripheral and output specified data. The UART should be used to simulate data being sent to the server. Be careful to ensure that the UART is initialized to the correct baud rate and serial configuration.

**What did you do particularly well?**

The code was implemented efficiently and with minimal complexity. We were able to achieve successful implementation of all the peripherals with accurate temperature readings and outputs with precise timing on the interrupts as well as the button functionality.

**Where could you improve?**

An improvement to the system would be to add Wi-Fi functionality to the thermostat to be able to operate it remotely. The CC3220S is capable of providing that feature and this will be a good next step for this project

**What tools and/or resources are you adding to your support network?**

The knowledge of using peripherals and how to program microcontrollers are some of the best skills and tools that this course has taught me.

**What skills from this project will be particularly transferable to other projects and/or course work?**

The use of object oriented programming, integrating peripherals, and implemeting a task scheduler are all relevant skills learned in this module that will transfer well into other computer science projects, especially those that involve system architecture. 

**How did you make this project maintainable, readable, and adaptable?**

This project utilized the core concepts of object oriented programming by inheriting C++ modules and applying methods and functions.


