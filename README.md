# SCANNER.ino
#include <Servo.h>

int buzzer=7;
int count = 0;
char c;
String id;
Servo myservo;

void setup() {
  Serial.begin(9600);
  myservo.attach(9);
  myservo.write(0);
  pinMode(9, OUTPUT);
  pinMode(buzzer,OUTPUT);
  Serial.println("Please scan your RFID TAG");
 
}

void loop() {
  while(Serial.available()>0)
  {
    c = Serial.read();
   count++;
   id += c;
   if(count == 12)  
    {
      Serial.print(id);
      //break;
     
      if(id=="AB123456789A")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(9,HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789B")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(9, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789C")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(9, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789D")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(9, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789E")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(9, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789A")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(9, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789F")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(9, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789G")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789H")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789I")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789J")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789K")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789L")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789M")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789N")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789O")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789P")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789Q")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789R")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789S")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789T")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789U")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789V")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789W")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789X")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789Y")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789Z")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789a")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789b")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789c")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789d")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
       if(id=="AB123456789e")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789f")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789g")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789h")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789i")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789j")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789k")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789l")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789m")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789n")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789o")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789p")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789q")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789r")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789s")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789t")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789u")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789v")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789w")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(13, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
        if(id=="AB123456789x")  //Define valid tag id here
      {
        Serial.println("Valid TAG");
        digitalWrite(9, HIGH);
        digitalWrite(buzzer,LOW);
        myservo.write(180);
        delay(3000);
        myservo.write(0);  
      }
      else
      {
      digitalWrite(9, LOW);
      digitalWrite(buzzer,HIGH);
      delay(1000);
      digitalWrite(buzzer,LOW);
      Serial.println("Invalid TAG");
      myservo.write(0); 
      }
   
    }
  }
  count = 0;
  id="";
  delay(500);

}
