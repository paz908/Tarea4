# Tarea4.1
// mi primer codigo
// 2022 04 05
// Paz
// Arduino Uno

int lucecita = 13; 






void setup() {
  // put your setup code here, to run once:
pinMode (lucecita, OUTPUT); 







}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(lucecita, HIGH);
delay(1000);

digitalWrite(lucecita, LOW);
delay(1000/3);


}
