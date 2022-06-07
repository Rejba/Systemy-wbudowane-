# Systemy-

wbudowane-



Blinks
‡define triglin 3 //attach pin D3 Arduino to pin Trig of HC-SR04
void setup () [
//Declaring LED pin as output
pinMode (led pin, OUTPUT) ;
pinMode (led pinl, OUTPUT) ;
pinMode (trigPin, OUTPUI) ; // Sets the triglin as an OUIPUT
pinMode (echoPin, INPUT); // Sets the echobin as an INPUT
Serial.begin (9600); // // Serial Communication is starting with 9600 of baudrate speed
void 100p0) {
// Clears the triglin condition
digitalwrite (trigPin, LOW) ;
delayMicroseconds(2);
/ Sets the triglin HIGH (ACTIVE) for 10 microseconds
digitalWrite (trigPin, HIGH) ;
delayMicroseconds (10) ;
digitalWrite(triglin, LOW) ;
// Reads the echoin, returns the sound wave travel time in microseconds
duration = pulseIn (echoPin, HIGH) :
// Calculating the distance
distance = duration * 0.034 / 2; // Speed of sound wave divided by 2 (go and back)
// Displays the distance on the Serial Monitor
Serial.print ("Distance:
");
Serial.print (distance) :
Serial.println(" cm") ;
if (distance >= 50 ) {
miganie = 5;
if (distance >= 30 sc distance < 40) [
miganie=
4;
if (distance ›= 20 as distance < 30) (
miganie = 3:
if (distance >= 10 ss distance < 20) (
miganie = 2;
if (distance >=
0 ss distance
< 10) 
