# LED Blink

## Description
This project demonstrates a basic LED blinking program using an Arduino board. The LED is connected to a digital output pin and is programmed to turn ON and OFF at regular intervals, creating a blinking effect.

This project helps beginners understand the fundamentals of Arduino programming, including digital output control and timing using delay functions.

## Components Required
- Arduino board
- LED
- Resistor (220Ω or 330Ω)
- Jumper wires

## Connections
- Connect the LED positive (long leg) to pin 13 of the Arduino
- Connect the LED negative (short leg) to GND through a resistor

## Code
```cpp
void setup() {
  pinMode(13, OUTPUT); // Set pin 13 as output
}

void loop() {
  digitalWrite(13, HIGH); // Turn LED ON
  delay(1000);            // Wait for 1 second
  digitalWrite(13, LOW);  // Turn LED OFF
  delay(1000);            // Wait for 1 second
}
Working :
The LED turns ON for 1 second and OFF for 1 second repeatedly, creating a blinking effect.
Conclusion :
This is a beginner-level project that introduces basic Arduino concepts and hardware interfacing.
