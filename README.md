# Connecting-ESP8266-to-Mobile-Hotspot
This was the second Activity Set in my second workshop conducted by my university as a part of my subject, Engineering Explorations. I have given a step by step guide in this repo as to how I was able to connect ESP8266 Microcontroller to my mobile wifi hotspot, and so can you!
<br><br>
I strongly suggest the viewers to go through this README.md file to effectively understand the process to connect ESP8266 Microcontroller to wifi.
<br><br>


<h1>Arduino IDE Setup</h1>
<br>
<h3>Step 1 : Setup the Arduino IDE to make it compatible to work with ESP8266</h3>
<br>
<p>1. Go to "file" and select "preferences"</p><br>
<p>2. Under "preferences" type the following line into the "Additional Boards Manager URLs"</p><br>
<p>http://arduino.esp8266.com/stable/package_esp8266com_index.json</p><br>
<p>3. Click "OK" to save changes</p><br>
<p>4. Go to "Tools" select "Boards" and navigate to "Boards Manager"</p><br>
<p>5. Search for "ESP8266" and install the library</p><br>
<p>6. Once the installation is complete, restart your ARDUINO IDE</p><br>
<p>7. Once you have reopened Arduino IDE, navigate to "Tools" > "Boards" > "esp8266" > "Node MCU 1.0 (ESP-12E Module)"</p><br>
<p>You may also choose "Node MCU 0.9 (ESP-12 Module)" depending on the options available in your IDE</p><br>
<p>8. Next Plug in the USB to Micro USB cable to your computer device and select the required port from where you will export your code into ESP8266</p>

<h1>Exporting the code to ESP8266</h1>
<br>
<p>Use the code file provided in this repo to connect ESP8266 to your mobile hotspot. Keep the following things in mind</p>
<br>
<p>1. Make sure ESP8266 is connected to your device and your IDE is open and working</p>
<p>2. You have 210x drivers installed in your computer device</p>
<p>3. Make sure to make necessary changes to the code where ever required</p>
<p>4. Make sure that your ESP8266 is not connected to any other wifi network already</p>

<h1>Getting the Output</h1><br>
<p>Export the code to ESP8266 as you would normally do and once the build is complete, you will see that ESP8266 is connected to the wifi</p>


