# 🤖 Arduino IoT Kit

A hands-on **Arduino IoT learning kit** designed for students, beginners, educators, and hobbyists to learn electronics, programming, wireless communication, sensors, and IoT through practical projects.

The kit combines an **Arduino Uno R3**, sensors, actuators, communication modules, motor-control components, and supporting hardware to help learners progress from basic electronics to connected IoT applications.



## 📖 Manual

This repository includes a complete **Arduino IoT Kit Manual** containing component information, circuit connections, programming examples, project instructions, and working explanations.

> 📘 **Manual:** The detailed project manual is available in the [`Manual/`](./Manual/) folder.



## ✨ Features

* 🔌 Beginner-friendly electronics projects
* 🤖 Arduino-based robotics and automation
* 📡 Bluetooth and Wi-Fi communication
* 🌡️ Sensor-based monitoring systems
* 🏠 Smart home automation
* 🌱 Smart irrigation
* 🌤️ Weather monitoring
* ⚠️ Gas leakage detection
* 🌧️ Rain monitoring
* 📺 IR remote-controlled systems
* 🚗 Bluetooth and IR robot car projects
* 🔐 Password-based security systems


## 📚 What This Kit Covers

| Section                 | Description                                                |
| ----------------------- | ---------------------------------------------------------- |
| **Introduction**        | Understanding Arduino IoT kits and their applications      |
| **Component Guide**     | Overview of the electronic components included in the kit  |
| **Safety Instructions** | Essential safety guidelines for working with electronics   |
| **Project Tutorials**   | 14 hands-on Arduino, Bluetooth, Wi-Fi, and IR projects     |
| **Package Contents**    | Complete list of components included in the kit            |
| **Getting Started**     | Arduino IDE setup, libraries, and programming instructions |



## 🗂️ Repository Structure


Arduino-IoT-Kit/
│
├── README.md
│
├── Manual/
│   └── Arduino-IoT-Kit-Manual.pdf
│
├── Projects/
│   ├── 01-Bluetooth-Smart-Home/
│   ├── 02-Bluetooth-Car/
│   ├── 03-Bluetooth-Password-Door-Lock/
│   ├── 04-Bluetooth-Voice-Control/
│   ├── 05-Bluetooth-RGB-Controller/
│   ├── 06-IoT-Weather-Monitoring/
│   ├── 07-IoT-Smart-Irrigation/
│   ├── 08-IoT-Home-Automation/
│   ├── 09-IoT-Gas-Leakage-Alert/
│   ├── 10-IoT-Energy-Monitoring/
│   ├── 11-IoT-Rain-Monitoring/
│   ├── 12-IR-Remote-Menu/
│   ├── 13-IR-Robot-Car/
│   └── 14-IR-Password-System/





# 🎯 Who Is This Kit For?

### 👨‍🎓 Beginners

No previous electronics or programming experience is required.

### 🏫 Students

Suitable for school, college, university, STEM, robotics, and IoT learning.

### 🛠️ Hobbyists

Experiment with sensors, automation, robotics, and wireless communication.

### 👩‍🏫 Teachers

Use the projects as practical activities or as a structured IoT curriculum.



# 🧠 Learning Outcomes

After completing the projects, learners will be able to:

* Understand how sensors collect information from the environment
* Program an **Arduino Uno** using the Arduino IDE
* Connect and control LEDs, motors, buzzers, relays, and other actuators
* Interface different sensors with Arduino
* Use Bluetooth for wireless communication
* Use ESP8266 for Wi-Fi and IoT applications
* Send and monitor sensor data using IoT platforms
* Build basic automation and monitoring systems
* Control robots using wireless interfaces
* Debug basic hardware and software problems
* Develop practical electronics and IoT problem-solving skills



# 🔧 Kit Components

## Main Components

| Component          | Description                                                    |
| ------------------ | -------------------------------------------------------------- |
| **Arduino Uno R3** | Main microcontroller board based on ATmega328P                 |
| **USB Cable**      | Programming and power connection                               |
| **Jumper Wires**   | Male-to-male, male-to-female, and female-to-female connections |
| **Resistor Kit**   | 30 different resistor values for circuit applications          |
| **Breadboard**     | Solderless circuit prototyping                                 |

## 💡 Output Components

| Component          | Description                                    |
| ------------------ | ---------------------------------------------- |
| **LEDs**           | Red, Green, Blue, White, and Yellow LEDs       |
| **RGB LED**        | Produces multiple colors using RGB control     |
| **Buzzer**         | Audio indication and alert generation          |
| **16×2 LCD**       | Text display with I2C interface                |
| **TM1637 Display** | 4-digit numeric display                        |
| **Servo Motor**    | Precise angular movement, typically 0°–180°    |
| **DC Motor**       | Continuous rotational movement                 |
| **BO Motor**       | Geared DC motor for robotic applications       |
| **Water Pump**     | Used for irrigation and water-control projects |
| **Fan Module**     | Cooling and airflow applications               |

## 📡 Communication Modules

| Module                   | Description                                                         |
| ------------------------ | ------------------------------------------------------------------- |
| **HC-05 Bluetooth**      | Wireless communication with smartphones and other Bluetooth devices |
| **ESP8266 ESP-12E**      | Wi-Fi connectivity for IoT applications                             |
| **IR Remote + Receiver** | Infrared wireless control                                           |

## 🌡️ Sensors

| Sensor                   | Description                                      |
| ------------------------ | ------------------------------------------------ |
| **HC-SR04 Ultrasonic**   | Distance measurement using ultrasonic waves      |
| **DHT11**                | Temperature and humidity measurement             |
| **LDR**                  | Light intensity detection                        |
| **IR Sensor**            | Object detection and line-following applications |
| **PIR Sensor**           | Human motion detection                           |
| **Soil Moisture Sensor** | Detects soil moisture level                      |
| **MQ-2 Gas Sensor**      | Detects smoke and combustible gases              |
| **Rain Sensor**          | Detects water/rain                               |
| **Touch Sensor**         | Capacitive touch detection                       |
| **Sound Sensor**         | Detects changes in sound level                   |

## ⚙️ Motor & Control Components

| Component              | Description                                       |
| ---------------------- | ------------------------------------------------- |
| **L293D Motor Driver** | Controls DC motors using Arduino                  |
| **L298N Motor Driver** | Dual H-bridge motor driver for robot applications |
| **Relay Module**       | Electrically controlled switching                 |
| **Wheels**             | 65 mm robot wheels                                |
| **Caster Wheel**       | Supports robot movement                           |
| **Robot Chassis**      | Acrylic platform for robot assembly               |

## 🔋 Power Components

| Component        | Description                          |
| ---------------- | ------------------------------------ |
| **9V Battery**   | Portable power source                |
| **Battery Clip** | Connects 9V battery to circuits      |
| **DC Jack Clip** | Provides a DC barrel-jack connection |



# 🚀 Projects

The kit contains **14 hands-on projects** divided into three categories.

| Category           | Projects       |
| ------------------ | -------------- |
| 📱 **Bluetooth**   | Projects 1–5   |
| 📡 **IoT / Wi-Fi** | Projects 6–11  |
| 📺 **IR Control**  | Projects 12–14 |



## 📱 Bluetooth Projects

### 1. 🏠 Bluetooth Smart Home Control

Control appliances using a smartphone through Bluetooth.

**Components:** Arduino Uno, HC-05, LED, Relay Module, Buzzer, Resistors

| Command | Action     |
| ------- | ---------- |
| `a`     | Light ON   |
| `A`     | Light OFF  |
| `B`     | Fan ON     |
| `b`     | Fan OFF    |
| `C`     | Buzzer ON  |
| `c`     | Buzzer OFF |



### 2. 🚗 Bluetooth Car

Build a smartphone-controlled robot car.

**Components:** Arduino Uno, HC-05, L298N, DC Motors, Wheels, Robot Chassis

| Command | Action   |
| ------- | -------- |
| `F`     | Forward  |
| `B`     | Backward |
| `L`     | Left     |
| `R`     | Right    |
| `S`     | Stop     |



### 3. 🔐 Bluetooth Password Door Lock

Create a password-protected electronic door-lock system.

**Components:** Arduino Uno, HC-05, Servo Motor, Buzzer

**Example Password:**


### 4. 🎤 Bluetooth Voice-Controlled System

Control appliances using voice commands transmitted through Bluetooth.

**Components:** Arduino Uno, HC-05, Relay Module, LED, Buzzer

| Voice Command | Action          |
| ------------- | --------------- |
| `light on`    | Turn ON light   |
| `light off`   | Turn OFF light  |
| `fan on`      | Turn ON fan     |
| `fan off`     | Turn OFF fan    |
| `buzzer on`   | Activate buzzer |
| `buzzer off`  | Stop buzzer     |



### 5. 🌈 Bluetooth RGB LED Controller

Control an RGB LED using smartphone-based controls.

**Components:** Arduino Uno, HC-05, RGB LED, Resistors

|   R |   G |   B | Color  |
| --: | --: | --: | ------ |
| 255 |   0 |   0 | Red    |
|   0 | 255 |   0 | Green  |
|   0 |   0 | 255 | Blue   |
| 255 | 255 |   0 | Yellow |
| 255 | 255 | 255 | White  |
|   0 |   0 |   0 | OFF    |



# 📡 IoT / Wi-Fi Projects

### 6. 🌤️ IoT Weather Monitoring System

Monitor temperature and humidity remotely using an Arduino and ESP8266.

**Components:** Arduino Uno, ESP8266, DHT11, Resistor

**Possible IoT Platforms:**

* ThingSpeak
* Blynk
* Adafruit IO



### 7. 🌱 IoT Smart Irrigation System

Automatically control plant watering based on soil moisture.

**Components:** Arduino Uno, ESP8266, Soil Moisture Sensor, Relay Module, Water Pump

**Features:**

* 📊 Monitor soil moisture
* 💧 Automatically control the water pump
* 🎛️ Manual pump control
* ⚙️ Configure moisture threshold
* 🔔 Receive alerts



### 8. 🏠 IoT Home Automation

Control appliances through a web interface using ESP8266.

**Components:** Arduino Uno, ESP8266, 2-Channel Relay Module

| URL Command | Action    |
| ----------- | --------- |
| `/lightON`  | Light ON  |
| `/lightOFF` | Light OFF |
| `/fanON`    | Fan ON    |
| `/fanOFF`   | Fan OFF   |



### 9. ⚠️ IoT Gas Leakage Alert System

Detect gas or smoke and provide local and remote alerts.

**Components:** Arduino Uno, ESP8266, MQ-2 Gas Sensor, Buzzer, LED

**Alert Features:**

* 🔊 Local buzzer alert
* 💡 LED indication
* 📱 Remote notification



### 10. ⚡ IoT Energy Monitoring System

Monitor electrical parameters using Arduino and ESP8266.

**Components:** Arduino Uno, ESP8266, Potentiometer

Example calculation:


Voltage = (Analog Value / 1023) × 5

Power = Voltage × Constant


> **Note:** The calculation above is a simplified learning example. Actual electrical power measurement requires an appropriate voltage/current sensing circuit and proper calibration.



### 11. 🌧️ IoT Rain Monitoring Station

Monitor rainfall conditions remotely.

**Components:** Arduino Uno, ESP8266, Rain Sensor, LED

**Dashboard Information:**

* Rain intensity
* Historical graph
* Real-time sensor values


# 📺 IR Projects

### 12. 📺 IR Remote Menu System

Navigate through menu options using an IR remote and display the selected option on a 16×2 LCD.

**Components:** Arduino Uno, IR Receiver, IR Remote, 16×2 LCD

| Button   | Function           |
| -------- | ------------------ |
| **UP**   | Next menu item     |
| **DOWN** | Previous menu item |
| **OK**   | Select option      |



### 13. 🤖 IR Controlled Robot Car

Control a robot car using an IR remote.

**Components:** Arduino Uno, IR Receiver, L298N, DC Motors, Robot Chassis

| Button    | Action   |
| --------- | -------- |
| **UP**    | Forward  |
| **DOWN**  | Backward |
| **LEFT**  | Left     |
| **RIGHT** | Right    |
| **OK**    | Stop     |

### 14. 🔑 IR Password System

Create a password-based security system using an IR remote.

**Components:** Arduino Uno, IR Receiver, IR Remote, Servo Motor, Buzzer

**Example Password:**

1 → 2 → 3 → 4 → OK




# ⚠️ Safety Instructions

> **⚠️ Important:** Always follow proper electrical and laboratory safety practices when working with electronic circuits.

1. ✅ Check all circuit connections before applying power.
2. ✅ Use a compatible power supply for each component.
3. ✅ Avoid short circuits on the breadboard.
4. ✅ Check the polarity of LEDs, batteries, sensors, and other components.
5. ✅ Do not exceed the voltage or current rating of any component.
6. ✅ Disconnect power before changing circuit connections.
7. ✅ Do not touch exposed conductors while the circuit is powered.
8. ✅ Immediately disconnect power if you notice overheating, smoke, burning smell, or unusual behavior.
9. ✅ Motors, pumps, and relays may require a separate suitable power supply.
10. ✅ Never connect mains/high-voltage appliances directly to Arduino pins. Use appropriately rated isolation and switching hardware.



# 📦 Package Includes

| Quantity | Component                                         |
| -------: | ------------------------------------------------- |
|       1× | Arduino Uno R3                                    |
|       1× | ESP8266 Wi-Fi Module                              |
|       1× | HC-05 Bluetooth Module                            |
|       1× | USB Cable                                         |
|       2× | 9V Battery                                        |
|       1× | 9V Battery Clip                                   |
|       1× | DC Jack Clip                                      |
|       1× | Breadboard                                        |
|      90× | Jumper Wires                                      |
|       1× | Resistor Kit – 30 different values                |
|      10× | LEDs – Red, Green, Blue, White, Yellow, RGB, 5 mm |
|       3× | RGB LED                                           |
|       3× | Push Buttons                                      |
|       1× | Buzzer                                            |
|       1× | HC-SR04 Ultrasonic Sensor                         |
|       1× | DHT11 Temperature & Humidity Sensor               |
|       1× | LDR                                               |
|       1× | IR Sensor Module                                  |
|       1× | PIR Motion Sensor                                 |
|       1× | Soil Moisture Sensor                              |
|       1× | Gas Sensor                                        |
|       1× | Sound Sensor                                      |
|       1× | Rain Drop Sensor                                  |
|       1× | Touch Sensor                                      |
|       1× | Relay Module                                      |
|       1× | SG90 Servo Motor                                  |
|       1× | DC Motor                                          |
|       1× | Fan Module                                        |
|       1× | Water Pump                                        |
|       1× | L298N Motor Driver                                |
|       2× | BO Motors – Dual Shaft, 100 RPM                   |
|       2× | Wheels – 65 mm                                    |
|       1× | Acrylic Robot Chassis                             |
|       1× | Caster Wheel                                      |
|       1× | IR Remote + Receiver Kit                          |
|       1× | 16×2 LCD with I2C – Address `0x27`                |



# 🛠️ Getting Started

## Prerequisites

### Arduino IDE

Download and install the Arduino IDE:

**https://www.arduino.cc/en/software**

### Required Hardware

* Arduino Uno R3
* USB cable
* Arduino IoT Kit components
* Computer

### Optional Mobile Applications

For Bluetooth projects, compatible applications include:

* Bluetooth Terminal
* Arduino Bluetooth Controller
* Serial Bluetooth Terminal



## 📥 Installation

### 1. Clone the Repository


### 2. Open Arduino IDE

Launch the Arduino IDE after installing it.

### 3. Install Required Libraries

Depending on the project, install the required libraries:


DHT sensor library
LiquidCrystal I2C
Servo
IRremote
ESP8266WiFi


> **Note:** Some libraries are included with the Arduino environment or board package, while others need to be installed through the Arduino IDE Library Manager.

### 4. Connect Arduino

Connect the Arduino Uno to your computer using the USB cable.

### 5. Select Board

In Arduino IDE:

Tools → Board → Arduino Uno


### 6. Select Port

Select the COM port corresponding to your Arduino board:


Tools → Port → COMx


### 7. Upload the Program

Open the required project folder, load the `.ino` file, verify the circuit connections, and upload the program.



# 📖 How to Use the Manual

Each project in the manual is designed to be completed step by step.

For every project:

1. Read the project objective.
2. Check the required components.
3. Review the circuit connections.
4. Build the circuit carefully.
5. Open the provided Arduino code.
6. Install the required libraries.
7. Upload the program.
8. Test the project.
9. Read the working explanation.
10. Experiment by modifying the project.

### 💡 Experiment Further

Once a project works, try:

* Changing sensor thresholds
* Modifying timings
* Adding LEDs or buzzers
* Adding additional sensors
* Creating a mobile interface
* Connecting the project to an IoT platform
* Combining multiple projects



# 📁 Project Organization

Each project can follow this recommended structure:


Projects/
└── 01-Bluetooth-Smart-Home/
    ├── README.md
    ├── Code/
    │   └── Bluetooth-Smart-Home.ino
    ├── Circuit/
    │   └── circuit-diagram.png
    └── Images/
        └── project.jpg


This structure makes the repository easier for students and teachers to understand and maintain.


# 🤝 Contributing

Contributions and improvements are welcome.

### Contribution Workflow

1. Fork this repository.
2. Create a new branch:
3. Make your changes.
4. Commit your changes:
5. Push your branch:


# ⭐ Support

If you find this Arduino IoT Kit useful:

* ⭐ Star the repository
* 🍴 Fork the repository
* 🛠️ Build the projects
* 💡 Experiment with your own ideas
* 🤝 Contribute improvements



## 📘 Manual & Projects

| Resource                      | Description                                   |
| ----------------------------- | --------------------------------------------- |
| 📖 [`Manual/`](./Manual/)     | Complete Arduino IoT Kit manual               |
| 🤖 [`Projects/`](./Projects/) | Project code, circuit diagrams, and resources |
| 📄 [`README.md`](./README.md) | Repository overview and setup guide           |



**Made for learning, building, experimenting, and creating with Arduino and IoT.** 🤖💡📡
