# AI-Driven Surveillance Drone

## Introduction

**AI-Driven Surveillance Drone** is a major project focused on the concept and development of an intelligent unmanned aerial vehicle (UAV) for aerial surveillance. The project is based on a hexacopter platform and uses Agile Software Engineering as its development approach.

The repository contains the project's Software Requirements Specification (SRS), system diagram, and hexacopter flight-controller parameter configuration.

## Project Diagram

![AI-Driven Surveillance Drone project diagram](Doc/AIDSDASE.png)

## Software Requirements Specification

The Software Requirements Specification (SRS) documents the system requirements and intended behaviour of the project.

[**View / Download the SRS (PDF)**](Doc/SRS.pdf)

## Hexacopter Configuration

The repository includes the flight-controller parameter file:

[**Hexacopter Parameters List**](Parameters/Hexacopter%20Parameters%20List.param)

It contains configuration values related to the hexacopter frame, flight control, navigation, sensors, radio channels, battery monitoring, and flight behaviour.

> **Note:** Flight-controller parameters are hardware- and firmware-dependent. Review and validate the complete configuration for the target aircraft before loading or using it.

## Repository Structure

```text
Major-I/
├── Doc/
│   ├── AIDSDASE.png
│   └── SRS.pdf
├── Parameters/
│   └── Hexacopter Parameters List.param
├── LICENSE
└── README.md
```

## License

This project is licensed under the [MIT License](LICENSE).
