
# LED-Blink-Arduino

This project demonstrates a simple **LED blinking program** using **Arduino UNO**.  
It turns an LED ON and OFF at a regular interval of 1 second using the built-in LED (pin 13).

---

## Components Required
- Arduino UNO board  
- USB cable  
- Breadboard (optional)  
- LED (if not using the onboard LED)  
- Resistor (220Ω)

---

## Code Explanation
```c
int ledPin = 13;

void setup() {
  pinMode(ledPin, OUTPUT); // Set the pin as output
}

void loop() {
  digitalWrite(ledPin, HIGH); // Turn LED ON
  delay(1000);                // Wait 1 second
  digitalWrite(ledPin, LOW);  // Turn LED OFF
  delay(1000);                // Wait 1 second
}
