# Earthquake-detection-alarm-code
#include <Wire.h>
#include <Adafruit_Sensor.h>
#include <Adafruit_ADXL345_U.h>

// Create an instance of the accelerometer sensor
Adafruit_ADXL345_Unified accel = Adafruit_ADXL345_Unified();

// Threshold for earthquake detection
float threshold = 2.5;  // Adjust the threshold based on your needs

// Pin
