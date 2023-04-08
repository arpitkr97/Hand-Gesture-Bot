# Hand-Gesture-Bot

Components and supplies:

1 * Switch Actuator, APEM A01 series Illuminated Push-Button Switches,
1 * HC-05 Bluetooth Module,
1 * Dual H-Bridge motor drivers L293D,
1 * Ultrasonic Sensor - HC-SR04 (Generic),
1 * Inertial Measurement Unit (IMU) (6 deg of freedom),
1 * Slide Switch,
1 * Arduino UNO,
1 * Arduino Nano R3,
1 * Robot wheels,
1 * PCB's,
1 * Rechargeable Battery, Lithium Ion,
1 * 9V battery (generic),
1 * DC Motor, 12 V,
1 * Robot chassis.

Tools and machines:

1 * Soldering Station, 110 V,
1 * Solder Flux, Soldering,
1 * Solder Wire, Lead Free.

Apps and platforms:

Arduino IDE


The transmission unit:

Contains Arduino nano (not heavy to handle),
MPU6050 sensor, 
Bluetooth HC-05 module(master), 
Push-button, battery 9v,
All components are soldering in the PCB board. 



The reception unit:

Basically made of an Arduino UNO,
Bluetooth module(slave) :receiving data,
H-bridge l293d : control direction and speed of motors, 
9v battery to power the Arduino UNO and other components, 
12v to power the motors,
Ultrasonic sensor : an additional sensor to avoid crashes,
All components are soldering in the PCB board. 


