#include <Keyboard.h>
void setup() {
  Keyboard.begin();


  //Joystick and buttons pin allocations
  pinMode(0, INPUT_PULLUP); //Joystick Up
  pinMode(1, INPUT_PULLUP); //Joystick Down
  pinMode(2, INPUT_PULLUP); //Joystick Left
  pinMode(3, INPUT_PULLUP); //Joystick Right
  pinMode(4, INPUT_PULLUP); //Button 1
  pinMode(5, INPUT_PULLUP); //Button 2
  pinMode(6, INPUT_PULLUP); //Button 3
  pinMode(7, INPUT_PULLUP); //Button 4
  pinMode(8, INPUT_PULLUP); //Coin
  pinMode(9, INPUT_PULLUP); //Start
}


void loop() {


  // Button labels:
  int joystickUp = digitalRead(0);
  int joystickDown = digitalRead(1);
  int joystickLeft = digitalRead(2);
  int joystickRight = digitalRead(3);
  int button1 = digitalRead(4);
  int button2 = digitalRead(5);
  int button3 = digitalRead(6);
  int button4 = digitalRead(7);
  int button5 = digitalRead(8);
  int button6 = digitalRead(9);
  int coin = digitalRead(10);
  int start = digitalRead(11);


  // Joystick Up - Arrow Up Key
  if (joystickUp == LOW) {
    Keyboard.press(218);
  }
  else {
    Keyboard.release(218);
  }


  // Joystick Down - Arrow Down Key
  if (joystickDown == LOW) {
    Keyboard.press(217);
  }
  else {
    Keyboard.release(217);
  }


  // Joystick Left - Arrow Left Key
  if (joystickLeft == LOW) {
    Keyboard.press(216);
  }
  else {
    Keyboard.release(216);
  }


  // Joystick Right - Arrow Right Key
  if (joystickRight == LOW) {
    Keyboard.press(215);
  }
  else {
    Keyboard.release(215);
  }


  // Button 1 - 1
  if (button1 == HIGH) {
    Keyboard.press(32);
  }
  else {
    Keyboard.release(32);
  }


  // Button 2 - 2
  if (button2 == HIGH) {
    Keyboard.press(10); delay(100);
  }
  else {
    Keyboard.release(10);
  }     

  // Button 3 - b
  if (button3 == HIGH) {
    Keyboard.press(98);
  }
  else {
    Keyboard.release(98);
  }


  // Button 4 - y
  if (button4 == HIGH) {
    Keyboard.press(49);
  }
  else {
    Keyboard.release(49);
  }

  // Button 5 - a
  if (button5 == HIGH) {
    Keyboard.press(97);
  }
  else {
    Keyboard.release(97);
  }

  // Button 6 - b
  if (button6 == HIGH) {
    Keyboard.press(120);
  }
  else {
    Keyboard.release(120);
  }


  // Coin - enter
  if (coin == HIGH) {
    Keyboard.press(13);
  }
  else {
    Keyboard.release(13);
  }


  // Start - spacebar
  if (start == HIGH) {
    Keyboard.press(32); delay(100);
  }
  else {
    Keyboard.release(32);
  }
  
}
