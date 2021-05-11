#include <Servo.h>


const int analogInPin = A0; 
int sensorValue = 0;               
int servoPin = 9;
int i = 0;

Servo servo;

void setup() {
 
servo.attach(servoPin);
}

void loop() {
 
  sensorValue = analogRead(analogInPin);           
 
  if(sensorValue < 600){
    for (int i = 0; i<=45; i++){
    servo.write(i);
    delay(0);
   }
   delay(3000);
  }
  servo.write(i); 
                     
}
