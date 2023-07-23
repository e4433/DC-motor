# DC-motor
int motorA1 = 2;
int motorA2 = 3;
void setup () {
  // put your setup code here
  pinMode(motorA1, OUTPUT);
  pinMode(motorA2, OUTPUT);

  digitalWrite(motorA1, HIGH);
  digitalWrite(motorA2, LOW);
}
void loop () {
   // put your main code here
}
