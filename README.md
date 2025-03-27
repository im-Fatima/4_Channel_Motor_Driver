# 4-Channel Motor Driver

## Overview
This is a **4-channel MOSFET-based motor driver** designed for controlling multiple motors efficiently. It is useful for applications like **drones, robotics, and automation**. The circuit is built using **SI2300DS MOSFETs**, supporting a **continuous maximum current of 3A per channel**. For higher current applications (up to **5A**), **AO3400** MOSFETs can be used.

## Specifications
| Parameter | Value |
|-----------|-------|
| **Operating Voltage** | 3V - 12V |
| **Continuous Max Current** | 3A (SI2300) / 5A (AO3400) |
| **Logic Voltage** | 3.3V - 5V |
| **MOSFET Used** | SI2300DS (Default) / AO3400 (For 5A Current) |

## Components Required
| Component | Specification |
|-----------|--------------|
| **MOSFETs** | SI2300DS (or AO3400 for 5A) |
| **Diodes** | 1N4148 |
| **Resistors** | 10KΩ & 1KΩ |
| **LED** | Red LED |

## Schematic Diagram
![Schematic](https://raw.githubusercontent.com/username/repository/main/schematic.png)

## 3D View of PCB
![3D View](https://raw.githubusercontent.com/username/repository/main/3d_view.png)

## 2D PCB Layout
![2D View](https://raw.githubusercontent.com/username/repository/main/2d_view.png)

## Real-Life Working Circuit
![Real Circuit](https://raw.githubusercontent.com/username/repository/main/real_life_circuit.png)

## Use Case: Drones
- **Motor Control**: Ideal for **controlling drone motors** efficiently using PWM signals.
- **Lightweight**: Uses compact MOSFETs, making it **suitable for aerial applications**.
- **High Efficiency**: Minimal heat dissipation and **low resistance switching**.


## How to Use
1. **Connect Power**: Supply **3V - 12V** to the motor driver.
2. **Connect Motors**: Attach up to **4 motors** to the output terminals.
3. **Logic Input**: Use a **3.3V or 5V** microcontroller (e.g., Arduino, ESP32) to control the motor.
5. **Test the Setup**: Ensure LEDs light up and motors respond correctly.




## Advantages
✔ **Compact & Lightweight** - Ideal for drone applications.  
✔ **Supports Up to 5A (AO3400)** - Can drive powerful motors.  
✔ **Low Power Consumption** - Efficient switching with MOSFETs.  

## Notes
- **If higher current is needed**, replace **SI2300DS** with **AO3400**.
- **Use proper heat dissipation techniques** for continuous high current applications.

## License
This project is open-source under the **MIT License**. Feel free to modify and improve it!
