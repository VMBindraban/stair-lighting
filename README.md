# Stair lighting

The idea is to use a wireless motion sensor to trigger the lightning in sequence.

- Motion sensor (zigbee) fires event to Home assistant
- Home assistant publishes event to MQTT
- Microcontroller subscribed to MQTT topic and triggers lights in sequence.

## Requirements

- ESP32 microcontroller
- Channel relay board module
- LED strips

