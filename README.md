# PDR-Inferior: A Basic Pedestrian Dead Reckoning System

PDR-Inferior is a simplistic implementation of a Pedestrian Dead Reckoning (PDR) system. This system estimates the position of a pedestrian based on their motion without the need for external positioning signals.

## Overview

This PDR system is designed to be straightforward and accessible for educational purposes or as a starting point for more sophisticated PDR algorithms. It uses data from an Inertial Measurement Unit (IMU) to calculate the trajectory of a pedestrian.

## Key Features

- **Basic Step Detection**: Identifies steps based on changes in acceleration.
- **Attitude Estimation**: Calculates the orientation of the pedestrian using IMU data.
- **Trajectory Calculation**: Estimates the path taken by integrating step data with orientation.
- **Simple Interface**: A user-friendly graphical interface for interacting with the system.

## Getting Started

To set up and run the PDR-Inferior system, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Yuyyyuuu/PDR-Inferior.git
   ```

2. **Install Dependencies**
   Ensure you have Python and the required libraries installed. The exact dependencies are listed in the `requirements.txt` file.

3. **Run the Application**
   Execute the main Python script to start the PDR system.

4. **Follow On-Screen Instructions**
   Use the provided GUI to interact with the system and perform PDR calculations.

## Usage

The system provides a graphical interface with a sequence of buttons to:
- Select operation mode (sample data or measured data).
- Read sensor data from a file.
- Display sensor data time diagrams.
- Calculate and display horizontal attitude angles.
- Smooth the calculated angles for better accuracy.
- Determine heading from magnetometer and gyroscope data.
- Detect footsteps and signify them on the diagram.
- Perform PDR and display the trajectory.

## Contributing

Contributions to PDR-Inferior are welcome. Please review the `CONTRIBUTING.md` file for guidelines on how to contribute to the project.

## License

This project is open source and released under the terms of the MIT License. See the `LICENSE` file for more information.

## Acknowledgements

The project is grateful for the open-source community's contributions and support in the development of this PDR system.
```

This README template provides a concise overview of the project, its main features, setup instructions, and guidelines for usage, contributing, and licensing. It is written to be accessible and informative without including any personal information or external links.
