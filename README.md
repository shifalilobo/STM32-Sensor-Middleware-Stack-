# STM32 Sensor Middleware Stack

Designed and implemented a sensor middleware stack for STM32 microcontrollers in C to abstract hardware interfaces and simplify sensor integration. Developed core modules including Sensor Manager, Data Acquisition Layer, Sensor Abstraction Layer, Event Handler, and Data Processing Engine. Verified functionality through software simulation and sensor data analysis.


## Overview

Designed and implemented a modular sensor middleware stack for STM32-based embedded systems. The project focuses on abstracting sensor interfaces, managing multiple sensors, and providing a unified API for sensor data acquisition and processing. The framework demonstrates concepts commonly used in industrial IoT, smart lighting, and environmental monitoring applications.


## Project Objectives

* Understand middleware architecture in embedded systems.
* Implement hardware abstraction for sensor interfaces.
* Support multiple sensors through a unified framework.
* Simulate sensor data acquisition and processing.
* Gain practical experience with modular firmware design.


## Key Features

### Developed a sensor middleware stack supporting:

* Sensor abstraction layer
* Multi-sensor management
* Data acquisition and processing
* Event handling
* Sensor configuration
* Threshold monitoring
* Fault detection
* Data logging

### Designed and integrated core modules including:

* Sensor Manager
* Sensor Abstraction Layer
* Data Acquisition Module
* Event Handler
* Data Processing Engine
* Threshold Monitor
* Fault Manager
* Logger Module

### Supported sensor interfaces:

* I2C
* SPI
* UART
* ADC

### Supported sensor types:

* Temperature Sensors
* Ambient Light Sensors
* Humidity Sensors
* Accelerometers
* Noise Sensors
* Proximity Sensors

### Functional capabilities:

* Sensor initialization
* Data acquisition
* Threshold-based event generation
* Sensor status monitoring
* Fault detection
* Data filtering and processing


## System Architecture

The sensor middleware stack provides a layer between application software and sensor drivers. Sensor data is acquired through hardware interfaces and processed before being provided to the application layer.


## STM32 Sensor Middleware Stack Architecture

<img width="3764" height="4200" alt="image" src="https://github.com/user-attachments/assets/fa739487-c342-48b6-b05e-7f3c313e74bb" />


## Core Modules

### Sensor Manager

Coordinates initialization and management of multiple sensors.

### Sensor Abstraction Layer

Provides a common interface for different sensor types.

### Data Acquisition Module

Handles periodic acquisition of sensor data.

### Event Handler

Generates events based on thresholds and sensor conditions.

### Data Processing Engine

Processes and filters acquired sensor data.

### Threshold Monitor

Detects threshold violations and abnormal values.

### Fault Manager

Monitors sensor failures and communication issues.

### Logger Module

Records sensor events and status information.


## Supported Interfaces

The middleware supports:

* I2C
* SPI
* UART
* ADC


## Sensor Types

The framework can be extended to support:

* Temperature Sensors
* Humidity Sensors
* Ambient Light Sensors
* Accelerometers
* Noise Sensors
* Proximity Sensors


## Directory Structure

```text
STM32-Sensor-Middleware-Stack
│
├── Core
│   ├── Src
│   │   ├── main.c
│   │   ├── sensor_manager.c
│   │   ├── sensor_abstraction.c
│   │   ├── data_acquisition.c
│   │   ├── event_handler.c
│   │   ├── data_processing.c
│   │   ├── threshold_monitor.c
│   │   ├── fault_manager.c
│   │   └── logger.c
│   │
│   └── Inc
│       ├── sensor_manager.h
│       ├── sensor_abstraction.h
│       ├── data_acquisition.h
│       ├── event_handler.h
│       ├── data_processing.h
│       ├── threshold_monitor.h
│       ├── fault_manager.h
│       └── logger.h
│
├── Drivers
│
├── test
│   ├── acquisition_test.c
│   ├── threshold_test.c
│   └── interface_test.c
│
├── docs
│   ├── architecture.png
│   ├── data_flow.png
│   ├── sensor_interfaces.png
│   └── execution_trace.png
│
└── README.md
```


## Verification

Performed functional verification using software-based test cases to validate:

* Sensor initialization
* Data acquisition
* Threshold monitoring
* Event generation
* Sensor fault detection
* Interface communication
* Data processing functionality


## Tools & Technologies

* Embedded C
* STM32
* I2C
* SPI
* UART
* ADC
* STM32CubeIDE
* Git
* GitHub


## Applications

This middleware stack can be applied in:

* Smart Lighting Systems
* Environmental Monitoring
* Industrial Automation
* Battery Management Systems
* IoT Devices
* Sensor Hubs
* Condition Monitoring Systems


## Learning Outcomes

Through this project, I gained practical understanding of:

* Middleware architecture
* Hardware abstraction layers
* Multi-sensor integration
* Interface protocols
* Event-driven firmware design
* Sensor data acquisition
* Data processing techniques
* Modular embedded software architecture


## Outcome

Successfully demonstrated a modular sensor middleware stack for STM32 microcontrollers and gained hands-on experience in sensor abstraction, data acquisition, event handling, and firmware architecture. This project strengthened practical knowledge of scalable embedded software design commonly used in industrial and IoT applications.


## Future Enhancements

The following features can be incorporated to further enhance the middleware stack:

* FreeRTOS integration
* DMA-based data acquisition
* Sensor calibration support
* Moving average filtering
* BLE communication support
* CAN communication support
* Cloud connectivity
* Data visualization dashboard
* Low power optimization
* AI-based anomaly detection

