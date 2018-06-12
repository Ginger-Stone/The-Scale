# The-Scale
A Node MCU (ESP8266 WiFi Module),Load Cell, HX711, LCD(I2C) and Firebase project.

In this project, I made a picked data from my Load cell then amplified it using the HX711,
I used Node MCU as the Microcontroller as it is capable of connectivity (IoT things).
Using Firebase to collect the data from the Node MCU and Finally sent it to my Android app for some one to view and also to the LCD.

The Node MCU could be used via the ESPlorer where you use Lua programming Language or through Arduino IDE. Though Lua isn't hard, I opted for Arduino as most of the libraries and tools I required were already made and were easily found and I am more familiar with it.

I used Arduino-1.8.5 as the other IDEs gave me issues when I tried connecting to firebase.

My HX711 Connections were abit different from the ones suggested when I purchased the Load cell and HX711.

One thing I noted on the LCD connectivity was the address. It took me a while to figure it out. The address is gotten from the library you use. Its among the examples. 

I chose firebase due to its ease in intergration and the realtime syncing ability it provides.

