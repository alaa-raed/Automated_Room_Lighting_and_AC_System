# Automatic Room Lighting and Climate Control System

## Project Objective

The **Automatic Room Lighting and Climate Control System** aims to enhance energy efficiency and comfort in a room by integrating automated lighting control and temperature regulation. This system leverages sensors to manage lighting based on room occupancy and controls an air conditioner based on the room's temperature.

## Features

### Automatic People Counting
- **IR Sensors**: Two IR sensors are placed at entry and exit points to count the number of people entering and leaving the room. This count is used to control the lighting.

### Automatic Lighting Control
- **Lighting Management**: 
  - **No Occupants**: The room light is automatically turned off if no people are detected.
  - **One or More Occupants**: The room light is automatically turned on if at least one person is detected. The light remains on as long as there are people in the room.

### Temperature Sensor
- **Temperature Management**: 
  - **Below 20°C**: The air conditioner is turned off.
  - **20°C to 24°C**: The air conditioner operates at the first speed.
  - **25°C to 34°C**: The air conditioner operates at the second speed.
  - **Above 35°C**: The air conditioner operates at the third speed.

### LCD Display
- **Information Display**: The LCD screen shows the current temperature in Celsius and the number of people in the room.

### Lamp and Relay
- **Lamp Control**: The lamp’s operation is dependent on the number of people in the room.
- **Relay**: A relay is used to convert 5V control signals to 220V to power the lamp.

### Air Conditioner
- **Climate Control**: The air conditioner’s speed is adjusted based on the room temperature.

## Components

- **IR Sensors**: 2 units for people counting
- **Temperature Sensor**: Measures room temperature
- **LCD Display**: Shows temperature and occupancy
- **Lamp**: Controlled based on occupancy
- **Relay**: Converts 5V to 220V for lamp operation
- **Air Conditioner**: Regulates room temperature
- **Microcontroller**: Manages inputs from sensors and controls outputs

## Installation and Setup

1. **Hardware Setup**
   - Connect the IR sensors, temperature sensor, LCD display, lamp, relay, and air conditioner to the microcontroller as per the circuit diagram.

2. **Software Setup**
   - Upload the provided code to the microcontroller using a compatible programmer.
   - Configure the sensors and calibrate the system based on your room’s environment.

3. **Operation**
   - Ensure the system is properly powered.
   - Test each component to verify correct operation and integration.

## Contributing

Contributions are welcome! To improve the system, please fork the repository, make your changes, and submit a pull request. For issues or feature requests, open an issue in this GitHub repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Thanks to the open-source community for their libraries and tools which have facilitated the development of this project.
