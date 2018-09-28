# Blink-arduino
MIKE LOOK ARDUINO CODE for blink

/*

Your name: Elias Han
Date: 9/28/18
Project/assignment name: 'Blink Barry'
Description: Blink: Blinks an LED on and off
  13 = Pin for LED
  
  credit: http://www.arduino.cc/en/Tutorial/Blink
/*

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
