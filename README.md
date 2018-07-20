# Ultrasonic Obstacle Control

The following code has been made for an Arduino board. Use the "NewPing" library to measure the distance of 5 ultrasound sensors HC-SR04. 4 Sensors to measure lateral distances and one to measure height. If the lower sensor measures more than 1.5 meters, the control begins to act. If one of the lateral sensors measures a distance less than 1.5 meters, it sends a MAVLINK command from RCOverride, which overwrites the entries that the APM receives from the flight controller.
