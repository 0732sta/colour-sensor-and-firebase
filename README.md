# colour-sensor-and-firebase
Using tcs34725, nodemcu ESP8266, and connect with Firebase to store data in a real-time database.

Add 2 zip  library to your Arduino IDE :
1. An Arduino library for the [ESP8266 firebase](https://github.com/FirebaseExtended/firebase-arduino)
  Follow the tutorial for better [setup ESP8266 with firebase](https://www.youtube.com/watch?v=EsCkSNrWyq8)
  If having an error :
  NodeMCU ESP8266 kFirebaseFingerprint Error (Error Compiling For Board NodeMCU 1.0)
  Make sure change 
  * board managers : ESP8266 Board version is 2.7.4
  * Include library : Arduino Json Library Version is 5.x
  
2. An Arduino library for the [Adafruit TCS34725](https://www.arduino.cc/reference/en/libraries/adafruit-tcs34725/)
