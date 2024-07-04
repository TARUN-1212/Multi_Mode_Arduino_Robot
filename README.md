# Multi_Mode_Arduino_Robot
Multi-Mode Robot: Voice Control, Obstacle Avoidance, Line Following, and App Control



This repository contains the code and resources for a **multi-mode robot car** project! The robot can be controlled in various ways, including:

* **Voice Control:** Control the robot using simple voice commands.
* **Obstacle Avoidance:** The robot can navigate its environment by detecting and avoiding obstacles.
* **Line Following:** The robot can follow a designated line path using sensors.
* **IR Remote Control:** The robot can be controlled remotely using an Infrared (IR) remote. 
* **Android App Control:** Implement control through a user-friendly Android application.

**Features:**

* Multi-modal control for a versatile robot platform.
* Obstacle avoidance for safe navigation.
* Line following capabilities for specific path tracking.
* Open-source design for customization and exploration.

**Hardware Components**

This project utilizes the following hardware components:

* **Microcontroller:** Arduino UNO
* **Motors:** 4x DC Gear Motors
* **Motor Driver:** L298 Motor Driver
* **Sensors:**
    * 2x IR Sensors for line following
    * 1x HC-SR04 Ultrasonic Sensor for obstacle avoidance
* **Communication:**
    * HC-05 Bluetooth Module (for potential future functionalities)
    * IR Receiver Module for remote control
* **Control:**
    * MP3 Player IR Remote for controlling the robot
    * SG90 Servo Motor (for possible future functionalities)
* **Other:**
    * Ultrasonic Sensor Holder
    * Jumper Wires
    * On/Off Switch
    * 2x 18650 Battery Holder (2 Cell)
    * 2x 18650 Battery Cell (3.7V)

**Getting Started**

This repository provides the following resources to get you started building your robot car:

* Hardware schematics: Learn about how these components are connected.
* Codebase: Explore the code for core functionalities like obstacle avoidance and line following. 
* (Optional) Voice control implementation details: (placeholder, to be filled as you develop voice control functionality).

**Building Instructions**

1.  Review the hardware schematics and ensure you have all the necessary components listed above.
2.  Assemble the robot car following the schematics and wiring diagrams for the Arduino UNO, motor driver, sensors, and other components.
3.  Load the codebase onto your Arduino UNO (specific instructions will be added).
4.  (Optional) Develop and integrate the Android application code for smartphone control.

**Further Exploration**

This project lays the foundation for further development. Here are some ideas to expand your robot's capabilities:

* **Refine Voice Control:** Enhance the voice control functionality with a wider range of commands and improved accuracy.
* **Android App Integration:**  Integrate the Android application code for full smartphone control.
* **Advanced Obstacle Avoidance:**  Explore more sophisticated obstacle avoidance algorithms using additional sensors (e.g., ultrasonic sensors).
* **Sensor Fusion:**  Combine data from multiple sensors (e.g., line following sensors and obstacle avoidance sensors) for a more robust control system.
* **Servo Motor Implementation:**  Explore functionalities using the SG90 servo motor (e.g., implementing a gripper or a camera mount).
* **Bluetooth Communication:**  Develop functionalities using the HC-05 Bluetooth module (e.g., Bluetooth control from a smartphone app).

**Community**

We welcome contributions and improvements to this open-source project! Feel free to share your ideas, bug fixes, or new functionalities through pull requests.

**License**

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) (GPLv3).

This revised README file incorporates the specific parts you mentioned, providing a more detailed bill of materials for anyone looking to build their own robot car based on your project. It also highlights potential areas for future development using the additional components. 
