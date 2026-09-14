# Smart Irrigation System

A **Smart Irrigation System** is an automatic plant-watering system that monitors soil moisture and controls a water pump according to the moisture level of the soil.

The main goal of this project is to **save water, reduce manual work, and provide the right amount of water to plants automatically**.

## Features

*  Automatic plant watering
*  Soil moisture monitoring
*  Automatic water pump control
*  Real-time sensor monitoring
*  Reduces water wastage
*  Low-cost and easy to build
*  Can work without continuous human interaction

## Components Required

| Component            |    Quantity |
| -------------------- | ----------: |
| Arduino Uno          |           1 |
| Soil Moisture Sensor |           1 |
| Relay Module         |           1 |
| Water Pump           |           1 |
| Water Pipe           |           1 |
| Jumper Wires         | As required |
| Breadboard           |           1 |
| Power Supply         |           1 |
| Water Container      |           1 |

## Circuit Connections

### Soil Moisture Sensor

| Sensor Pin | Arduino |
| ---------- | ------- |
| VCC        | 5V      |
| GND        | GND     |
| AO         | A0      |

### Relay Module

| Relay Pin | Arduino       |
| --------- | ------------- |
| VCC       | 5V            |
| GND       | GND           |
| IN        | Digital Pin 7 |

The water pump is connected to the relay so that the Arduino can turn the pump **ON/OFF automatically**.


## How It Works

1. The soil moisture sensor measures the moisture level of the soil.
2. The Arduino reads the sensor value.
3. If the soil becomes dry, the Arduino turns the water pump **ON**.
4. Water is supplied to the plant.
5. When the soil becomes sufficiently wet, the Arduino turns the pump **OFF**.
6. This process repeats automatically.

##  Applications

*  Agricultural fields
*  Home gardens
*  Greenhouses
*  Nurseries
*  Smart gardens
*  Indoor plants
*  Automated farming
  ---
  
 ## Advantages

* Saves water
* Saves time
* Reduces human effort
* Automatic operation
* Low-cost implementation
* Easy to maintain
* Helps maintain suitable soil moisture

---

## Future Improvements

The system can be upgraded with:

*  Mobile app control
* IoT monitoring
* ESP8266/ESP32
* Cloud data storage
*  Weather-based irrigation
* Water-level sensor
* Temperature and humidity sensor
* Web dashboard
* Solar power

---

## Project Images

### 1. Smart Irrigation System
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-1.jpg)

### 2. Project Introduction
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-2.jpg)

### 3. Project Objectives
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-3.jpg)

### 4. Project Components/Materials
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-4.jpg)

### 5. Project Working Principle
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-5.jpg)

### 6. Project Implementation & Demonstration
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-6.jpg)

### 7. Project Learning Outcomes
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-7.jpg)

### 8. Project Applications & Future Scope
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-8.jpg)

### 9. Project Challenges & Solutions
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-9.jpg)

### 10. Project Question
![image alt](https://github.com/mdsabbirhossainsourav-alive/Smart-Irrigation-System/blob/main/image-10.jpg)

## Technologies Used

* **Arduino**
* **C/C++**
* **Soil Moisture Sensor**
* **Relay**
* **DC Water Pump**
---
##  License

This project is open-source and available for educational and personal use.
