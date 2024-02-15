# **Project 3: Windshield Wiper Subsystem**

Conor Fryer and Jake Ciocca

## **Description:**
In this project, we designed a comprehensive windshield wiper control system for a car to provide seamless functionality and user-centric behaviors. The ignition subsystem ensures the engine starts upon the driver's occupancy and ignition button push, lighting the Green LED (LD1) on the NUCLEO board, indicating the car is ready to start and the driver is in the car. Once the ignition button is pressed, the Green LED turns off, and the Blue LED (LD2) turns on, indicating the car is running. The engine remains running even if the driver exits the vehicle. The engine can be stopped by pushing and releasing the ignition button while the engine is running. The driver seat occupancy button is implemented on the breadboard and connected to D10 on the NUCLEO Board, while the ignition button is the USER button on the NUCLEO Board. A potentiometer on the breadboard is used to choose the windshield wiper mode, connected to the NUCLEO board's A0 pin, providing intuitive mode selection. Another potentiometer on the breadboard is used to control the LCD display's brightness, ensuring good visibility of what is being displayed. The LCD display on the breadboard is connected to the NUCLEO Board and will display the current mode the windshield wipers are in, giving clear visual feedback to the user. If the engine is running and a wiper mode is selected (HI, LO, INT, or OFF), the wipers operate accordingly with predefined parameters. The desired delay time for the INT mode is retrieved from the intermittent delay time selector. If the wiper mode selector is turned to OFF or the engine is turned off, ongoing wiper cycles are completed before returning the wipers to the 0-degree position, except in the INT mode where hesitations are maintained if ongoing. This system ensures efficient and intuitive control of windshield wiper operation, enhancing the overall driving experience and safety.


### **Code:**
As you can see, we modularized our code for better understandability and maintainability. 

#### **Testing Results:**
