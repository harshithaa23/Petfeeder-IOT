# Petfeeder


## Overview
An IoT-based pet feeder using the ESP32 microcontroller enables pet owners to remotely manage feeding schedules, monitor portions, and maintain a consistent feeding routine. This automated solution allows pet owners to ensure their pets' well-being through a convenient web interface.

## Features
- **Automated Feeding Schedule**: Configurable feeding times through a mobile app or web interface.
- **Portion Control**: Precise control over food portions to avoid overfeeding or underfeeding.
- **Remote Control and Monitoring**: Manage and monitor feedings from anywhere using Wi-Fi connectivity.
- **Data Logging**: Logs feeding history for insight into feeding patterns and pet health.
- **Smart Home Integration**: Compatible with smart home devices for enhanced control.

## Objectives
1. **Consistency**: Provide consistent feeding for pets, even when owners are away.
2. **Health Monitoring**: Track pet feeding habits to help in identifying health issues early.
3. **User-Friendly Interface**: Enable easy control and scheduling through a web application.
  
## Components
- **ESP32 Microcontroller**: Controls all feeder functions, including timing and portioning.
- **Servo Motor**: Dispenses food portions accurately.
- **LCD Display**: Shows feeding status and time.
- **DHT11 Sensor**: Monitors temperature and humidity around the feeder.

## Methodology
1. **ESP32 Setup**: Configured to handle Wi-Fi connections and MQTT for data transmission.
2. **Sensor Data Logging**: Collects and transmits data (e.g., temperature, humidity) to ThingSpeak.
3. **Web Interface**: Simple, user-friendly controls for feeding and schedule management.
4. **Feeding Mechanism**: Controlled by servo motor using Pulse Width Modulation (PWM) for accurate portion control.

## Applications
- **Convenience**: Easy feeding management while away from home.
- **Health Insights**: Allows monitoring of pet’s appetite and feeding habits.
- **Stress Reduction**: Pets receive timely meals without dependency on the owner's presence.

## Getting Started
1. **Set Up**: Follow the circuit diagram to connect all components.
2. **Configure ESP32**: Load the code and connect the ESP32 to your Wi-Fi.
3. **Launch the Web Interface**: Control feeding operations from a browser.
4. **Monitor Data**: View feeding logs and environmental data on the display.

## Future Improvements
- **Camera Integration**: Add a camera for live monitoring of pets during feeding.
- **Food Level Sensor**: Automatically alert owners when food supply is low.
- **Voice Control**: Integrate with Amazon Alexa or Google Assistant for hands-free operation.

## Technologies Used
- **MicroPython**: For programming the ESP32.
- **ThingSpeak**: Data storage and monitoring.
- **HTML/CSS**: For web-based control interface.

## License
This project is for educational purposes and aims to enhance pet care through IoT technology.
