# colour-sensor-and-firebase
Using tcs34725, nodemcu ESP8266, and connect with Firebase to store data in a real-time database.

Add 2 zip  library to your Arduino IDE :
1. An Arduino library for the [ESP8266 firebase](https://github.com/FirebaseExtended/firebase-arduino)<br>
  Follow the tutorial for better [setup ESP8266 with firebase](https://www.youtube.com/watch?v=EsCkSNrWyq8) 
2. An Arduino library for the [Adafruit TCS34725](https://www.arduino.cc/reference/en/libraries/adafruit-tcs34725/)
</br>
 If having an error :
 1.
  <br />
  NodeMCU ESP8266 kFirebaseFingerprint Error (Error Compiling For Board NodeMCU 1.0)
  <br /><br/>
  Make sure change 
  <br />
  <ol>
  <li>board managers : ESP8266 Board version is 2.7.4 </li>
  <li>Include library : Arduino Json Library Version is 5.x </li>
  </ol>
2. [Fairebase.failed() is always true with empty Firebase.error](https://github.com/FirebaseExtended/firebase-arduino/issues/474)
