//black track over white surface
int leftMotor=13;
int righMotor=12;
int rightEye=3;
int leftEye=4;
void setup(){
 pinMode(leftMotor,OUTPUT);
 pinMode(rightMotor,OUTPUT);
 pinMode(leftEye, INPUT);
 pinMode(rightEye, INPUT);
} 
void loop(){
 //forward
 if( digitalRead(rightEye)== HIGH && digitalRead(leftEye)==HIGH)
  { 
     digitalWrite(rightMotor, HIGH);
     digitalWrite(leftMotor, HIGH);
  }
//right
 if( digitalRead(rightEye)== LOW && digitalRead(leftEye)==HIGH)
  { 
     digitalWrite(rightMotor, LOW);
     digitalWrite(leftMotor, HIGH);
   }
//left 
 if( digitalRead(rightEye)== HIGH && digitalRead(leftEye)==LOW)
  { 
     digitalWrite(rightMotor, HIGH);
     digitalWrite(leftMotor, LOW);
   }
//stop
 if( digitalRead(rightEye)== LOW && digitalRead(leftEye)==LOW)
  { 
     digitalWrite(rightMotor, LOW);
     digitalWrite(leftMotor, LOW);
   }
}
