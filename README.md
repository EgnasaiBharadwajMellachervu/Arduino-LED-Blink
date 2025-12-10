This is a simple Arduino project that blinks an LED on pin 13. Includes schematic and code documentation.

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
