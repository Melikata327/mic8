# mic8
##ازمایش 9
#هدف:
بااستفاده از push button ال ای دی خاموش و روشن شود 
#شرح ارمایش
برروی برد بورد پوش باتن را گذاشته 
وبه موازات ان مقاومت متصل نموده،چون در پوش باتن به صورت موازی به هم دیگر متصل هستند.
در پوش باتن یک سر ان را به عدد 2 متصل کرده (واز قسمت دیگر ان به پایه 5 برد اونو متصل می نماییم) بعد ازان ال ای دی را وصل نموده (ازطریق ال ای دی بع پایه13 واز طریق ان مقاومت دیگری وصل کرده و پایه ان را به زمین(GND) وصل می کنیم








int ledPin = 2;
int led = 13;
 int  bouttonState=0;
void setup() {
  pinMode(ledPin,INPUT);
  pinMode(led, OUTPUT);


}


void loop() {
int a = digitalRead( butpin);

   if(a==HIGH)
  {


    digitalWrite(ledPin , HIGH);
  } else  {

  }



  digitalWrite(led , LOW);

}