# TinyML-and-Sign-Language
This project explores how TinyML can be used to interpret complex gestures with Visual-Gestural Communication (VGC).

## Hardware used:
  - Arduino nano 33 BLE
  - TTP223B Digital Capacitive Touch Sensor

## Code files:
  1. CE4172_Model Training
  2. IMU_Capture.ino - used to capture raw data using the Arduino nano. Reads the accelerometer, gyroscope and touch sensor inputs. Data is then copied into csv files.
  3. IMU_Classifier.ino - used with the trained model to inference gestures on the Arduino nano and output the results.

## References:
  https://github.com/arduino/ArduinoTensorFlowLiteTutorials/
