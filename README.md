# IoT_Compressor Project: This project is implemented to manage the parameters of compressor: vibration, temperature, humidity, pressure,...
We create 3 modules for this project:
- Module 1: Sensor_Node integrates the accelerometer sensor (ADXL345) to monitor the compressor vibration
- Module 2: Monitor_Machine_Node is used for reading and writing data between machine and application: Web and App via RS485 protocol.
- Module 3: Gateway_Node consist of SIM A7677 Module for 4G connection, Micro SD for data storage, W5500 for Ethernet Port and others. It likes the transfer station to summarize data and interact between Monitor_Machine_Node and Server.
