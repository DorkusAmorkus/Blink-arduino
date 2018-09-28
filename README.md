# Blink-arduino
MIKE LOOK ARDUINO CODE for blink

// Source: http://www.arduino.cc/en/Tutorial/Blink

// the setup function runs once when you press reset or power the board

void setup() {
 pinMode(13, OUTPUT); //sets up what PIN the positive end of the LED is
}

// 
void loop() {
  digitalWrite(13, HIGH);   // turns light on
  delay(1000);                       // keeps it on for 1000 milliseconds (one second)
  digitalWrite(13, LOW);    // turns light off
  delay(1000);                       // keeps it off for 1000 milliseconds (one second)
  }
