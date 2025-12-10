# Arduino-LED-Blink
A simple Arduino project that blinks an LED on pin 13. Perfect for beginners learning Arduino basics. Includes hardware schematic and code documentation.

## Project Overview
This is a beginner-friendly Arduino project that demonstrates the basics of controlling digital output pins. The LED blinks on and off at regular intervals using simple code.

## Hardware Requirements
- Arduino Board (Uno, Nano, or Mega)
- 1x LED (any color)
- 1x 220Ω Resistor
- Jumper wires
- USB cable for programming

## Circuit Diagram
```
Arduino Pin 13 --|--- LED Anode
                   |
                  220Ω Resistor
                   |
                 GND (Ground)
```

## Software Setup
1. Download the Arduino IDE from https://www.arduino.cc/en/software
2. Connect your Arduino board to your computer via USB
3. Select the correct board and port in the Arduino IDE
4. Upload the sketch to your Arduino

## Code
The main code blinks the LED with a 1-second interval:
```cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
```

## Features
- Simple and easy to understand
- Perfect for Arduino beginners
- Uses only built-in LED (no external circuit required)
- Great starting point for learning Arduino

## Author
Created as a learning project for Electronics & Instrumentation Engineering

## License
MIT License - feel free to use and modify
