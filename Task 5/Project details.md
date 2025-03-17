# Project name
Secure Saiyan
# Overview 
The Secure Saiyan provides a modern, secure method of entry, integrating technology to improve traditional locking mechanisms. The primary components include a 4×4 matrix keypad for user input, a VSD Squadron Mini for processing and verification, a servo motor to operate the door handle and an LCD screen to display the Status. When a user enters their passcode on the keypad, the VSD Squadron Mini validates the code against stored authorized code. If the passcode is correct, the VSD Squadron Mini triggers the servo motor to rotate the door handle, while the LCD displays UNLOCKED, thereby unlocking the door, else the LCD displays LOCKED, with the servo motor untriggered. This combination of electronic and mechanical elements ensures reliability and user-friendliness.
# Components required
-VSD Squadron Mini
-4×4 Matrix Keypad
-Servo Motor
-LCD Display
-Breadboard
-Jumper Wire
# Circuit connection

![image](https://github.com/user-attachments/assets/c76b30d1-4e14-4b77-bc9b-99276ad91e9c)

# Pin Connections
-wire 8->PD7
-wire 7->PD6
-wire 6->PD5
-wire 5->PD4
-wire 4->PD3
-wire 3->PD2
-wire 2->PD1

LCD display with I2C interface connections:
-GND (1)->VSD Squadron Mini GND
-VCC (2)->VSD Squadron Mini 5V
-SDA (3)->PC1(SDA Pin)
-SCL (4)->PC2(SCL Pin)

Servo Motor Connections:

Servo 5V -> VSD Squadron Mini 5V
Servo GND -> VSD Squadron Mini GND
Servo Input -> PC4







