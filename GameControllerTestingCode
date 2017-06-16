  #include <Keyboard.h>
  void setup() {  
  Serial.begin(9600);
  Serial.flush();  
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
  pinMode(8, INPUT_PULLUP); //Button 5  
  pinMode(9, INPUT_PULLUP); //Button 6
  pinMode(10, INPUT_PULLUP); //Coin
  pinMode(11, INPUT_PULLUP);  //Start
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
    Serial.println("joystickUp press 218");  
  }  
//  else {  
//    Serial.println("joystickUp release 218");  
//  }  
  
  
  // Joystick Down - Arrow Down Key  
  if (joystickDown == LOW) {  
    Serial.println("joystickDown print 217");  
  }  
  // else {  
//    Serial.println("joystickDown release 217");  
//  }  
  
  
  // Joystick Left - Arrow Left Key  
  if (joystickLeft == LOW) {  
    Serial.println("joystickLeft print 216");  
  }  
//  else {  
//    Serial.println("joystickLeft release 216");  
//  }  
  
  
  // Joystick Right - Arrow Right Key  
  if (joystickRight == LOW) {  
    Serial.println("joystickRight print 215");  
  }  
//  else {  
//    Serial.println("joystickRight release 215");  
//  }  
  
  
  // Button 1 - 1  
  if (button1 == HIGH) {  
    Serial.println("button1 print 49"); 
  }
//  else {  
//    Keyboard.release(10);  
//  }  

  
  // Button 2 - 2  
  if (button2 == HIGH) {  
    Serial.println("button2 print 50");  
  }  
//  else {  
//    Serial.println("button2 release 50");  
//  }  
  
  // Button 3 - b  
  if (button3 == HIGH) {  
    Serial.println("button3 print 98");  
  }  
//  else {  
//    Serial.println("button3 release 98");  
//  }  
  
  
  // Button 4 - y 
  if (button4 == HIGH) {  
    Serial.println("button4 print 121");  
  }  
  // else {  
//    Serial.println("button4 release 121");  
//  }  

  // Button 5 - a  
  if (button5 == HIGH) {  
    Serial.println("button5 print 97");  
  }  
//  else {  
//    Serial.println("button5 release 97");  
//  }

  // Button 6 - x 
  if (button6 == HIGH) {  
    Serial.println("button6 print 120");  
  }  
//  else {  
//    Serial.println("button6 release 120");  
//  }
  
  // Coin - enter  
  if (coin == LOW) {  
    Serial.println("coin print 13");  
  }  
//  else {  
//    Serial.println("coin release 13");  
//  }  
  
  
  // Start - spacebar  
  if (start == LOW) {  
    Serial.println("start print 32"); delay(100);  
  }  
//  else {  
//    Serial.println("start release 32");  
//  }  
    
}  
