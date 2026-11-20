# Exp-4: Interfacing-Analog-Output-With-Development-Board-And-Servo-Motor

### Name: Ashqar Ahamed S T
### Reg No.: 212224240018

## Aim:
To interface analog output with development board and servo motor.

## Component Required:

1. Tinkercad software.
2. Arduino Uno.
3. Micro Servo Motor.
4. Breadboard.


## Procedure:

1. Open Tinkercad Circuits and create a new circuit.
2. Place the Arduino Uno, breadboard and micro servo motor in the workspace.
3. Connect the 5V pin of the Arduino to the positive rail of the breadboard.
4. Connect the GND pin of the Arduino to the negative rail of the breadboard.
5. Connect the red wire of the servo motor to the 5V supply.
6. Connect the brown or black wire of the servo motor to GND.
7. Connect the orange or yellow signal wire of the servo motor to digital pin 9 of the Arduino.
8. Write the Arduino program using the Servo library to control the angular position of the motor.
9. Start the simulation and upload or run the program.
10. Observe the servo motor rotating to different angular positions (0° to 180°) based on the values given in the program.


## Program:

```
#include <Servo.h>

Servo myservo; // Object [myservo] of Servo Library is created
               // OOPs Concept

void setup()
{
  myservo.attach(9);
}

void loop()
{
  myservo.write(45);
  delay(1000); 
  myservo.write(90);
  delay(1000);
  myservo.write(135);
  delay(1000);
  myservo.write(180); // Servo Motor Can Rotate maximum 180 degree.
  delay(1000);
}

```


## Circuit Diagram:

<img width="1481" height="732" alt="Circuit Diagram" src="https://github.com/user-attachments/assets/a4532b5a-6b8c-498c-8700-4e40114c7c39" />


## Schematic:

<img width="1128" height="872" alt="Schematic" src="https://github.com/user-attachments/assets/3b3f6c81-73bd-41da-aa64-0bad818c09d2" />


## Output:

<img width="952" height="821" alt="Output" src="https://github.com/user-attachments/assets/ae40ca89-e04b-4089-9f77-c0b4a539ed4e" />

## Result:

Thus, a simulaiton to interface analog output with development board and servo motor was performed and executed successfully.
