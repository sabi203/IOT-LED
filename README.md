# IOT-LED
LED blinking esp32
void setup(){
  serial.begin(115200);
  pinmode(19,HIGH);
  )
void loop(){
 digitalwrite(19,HIGH);
 delay(1000);
 digitalwrite(19,LOW);
 delay(1000):
 }
