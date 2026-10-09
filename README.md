This is an ongoing project.

A small DIY quadcopter with ESP32-C3-SuperMini as flight controller and a Hobbywing 20A 4in1 ESC

The frame is designed with Fusion and is 3D printed

# System Overview
- The ESP32-C3 as the main processor processes sensor readings and calculated motor commands using the DShot600
- The MPU6050 provides accelerometer as well as gyroscope to the flight controller over I2C
- The NRF24L01 receives wireless commands from the controller
- The 4in1 ESC drives the four motors according to commands given by the flight controller
- The battery provides a stable 7.4V (2S) supply to the ESC and a stable 5V to the flight controller through the buck converter
