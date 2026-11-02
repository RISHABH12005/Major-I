# AI-Driven Surveillance Drone

A major project exploring the development of an **AI-driven surveillance drone using Agile Software Engineering**. This repository currently contains the project documentation and a hexacopter flight-controller parameter file.

## Project Overview

The project focuses on a hexacopter-based unmanned aerial vehicle (UAV) concept for aerial monitoring and surveillance. It brings together UAV configuration and software-engineering practices, with an emphasis on planning, requirements, iterative development, and verification.

The repository is currently documentation- and configuration-oriented. It does not yet contain application source code, an AI model, or a flight-control implementation. The capabilities described here are the project direction, not a claim that those features are already implemented.

## System Configuration

The parameter file contains flight-controller configuration values covering areas such as:

- **Frame configuration:** the `FRAME_CLASS` parameter is set to `2` (hexacopter).
- **Attitude and rate control:** roll, pitch, and yaw controller parameters.
- **Navigation and estimation:** EKF, GPS, compass, and barometer settings.
- **Power monitoring:** battery monitor, voltage, current, and failsafe-related values.
- **Radio and outputs:** RC channel mappings and servo/motor output functions.
- **Flight behaviour:** flight modes, Return-to-Launch, waypoint navigation, and logging.

These values are provided as a project configuration reference. They are not a universal or flight-ready setup. Validate every value against the exact airframe, autopilot hardware, firmware version, sensor installation, and operating conditions before use.

## Documentation

- **Software Requirements Specification:** [Open SRS](Doc/SRS.pdf)
- **Project diagram:** [View diagram](Doc/AIDSDASE.png)
- **Hexacopter parameters:** [View parameter file](Parameters/Hexacopter%20Parameters%20List.param)

## Development Approach

The project title identifies Agile Software Engineering as its development approach. A practical iterative workflow for this project can include:

1. **Requirements:** define surveillance use cases, operating constraints, system requirements, and acceptance criteria.
2. **Architecture:** document the UAV hardware, flight controller, communication links, data flow, and AI-processing components.
3. **Implementation:** develop and integrate individual components in small, reviewable increments.
4. **Verification:** test components in simulation and on the bench before controlled flight testing.
5. **Review and iteration:** evaluate test results, update requirements, and refine the next development increment.

## Safety Notice

UAV configuration directly affects aircraft behaviour. The included parameter file may contain hardware-specific, firmware-specific, or installation-specific values.

- Do not upload the parameter file to an aircraft without reviewing every parameter.
- Back up the aircraft's existing parameters before making changes.
- Confirm sensor calibration, motor order and direction, RC mapping, failsafe behaviour, and flight modes.
- Test in a suitable simulator and perform controlled pre-flight checks in a safe, legal test area.
- Follow applicable local aviation regulations and obtain required permissions.

**This repository is not flight certification or a guarantee of safe operation.** The project files are provided for educational and development purposes.

## Current Repository Status

At the time of writing, the repository contains supporting documentation, a project diagram, and a hexacopter parameter export. Source code, AI models, deployment instructions, and reproducible build or test procedures are not currently included.

As development progresses, this section should be updated with verified implementation details, demonstrations, test results, and setup instructions.

## Contributing

Contributions that improve the project documentation, requirements, configuration traceability, testing plans, or implementation are welcome.

1. Fork the repository.
2. Create a focused branch for your change.
3. Make and test your changes.
4. Open a pull request describing the change and its verification.

For parameter changes, include the target hardware and firmware context and explain why the change is required.

## License

This project is licensed under the [MIT License](LICENSE).

