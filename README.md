# TinyML-and-Sign-Language
This project explores how TinyML can be used to interpret complex gestures with Visual-Gestural Communication (VGC).

## Hardware used:
  - Arduino Nano 33 BLE
  - TTP223B Digital Capacitive Touch Sensor

## Code files:
  1. CE4172_Model Training - Used TensorFlow Lite to train the model to be used in the Arduino Nano.
  2. IMU_Capture.ino - Used to capture raw data using the Arduino Nano. Reads the accelerometer, gyroscope and touch sensor inputs. Data is then copied into csv files to be used to train a model.
  3. IMU_Classifier.ino - Used with the trained model to inference gestures on the Arduino nano and output the results.

## References:
  https://github.com/arduino/ArduinoTensorFlowLiteTutorials/

