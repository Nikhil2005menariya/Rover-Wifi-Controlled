# Rover-Wifi-Controlled
Process of this WIFI-controlled car
When this WIFI-controlled car is powered on, the Nodemcu board connects to the Blynk cloud via a WiFi connection. Then, when you press the Commands (Forward, Backward, Left, Right) buttons on the interface created in the Blynk app, those values will be sent to the Nodemcu board via the Blynk cloud. Then, the gear  motors rotate according to those values. The L298N motor driver board is used for this. Also, the speed of these motors can be controlled by the slider created in the Blynk app.

So, let’s make this smart car step by step. The required components are as follows.

 Nodemcu ESP8266 x 1 — Our Store  / Amazon
L298N motor driver x 1 — Our Store /  Amazon 
Gear motor x 4 — Our Store / Amazon 
Robot wheel x 4 —  Our Store  / Amazon 
Battery holder x 1 — Our Store /  Amazon
Li-ion battery  x 2 — Amazon /
Jumper wires —  Our Store / Amazon 
Breadboard  x 1 — Our Store / Amazon 
Foamboard piece  — Amazon / 
Disclosure: These Amazon links are Affiliate links. As an Amazon Associate, I earn from qualifying purchases.

Step 1
Firstly, identify these components.

How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions







Step 2
Secondly, glue the gear motors to the foam board, To do this, use the Glue gun.


How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

Step 3
Thirdly, attach the motor driver board to the top of the foam board. Afterward, connect the gear motors to the Motor driver board. For that, use the circuit diagram below.

How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

x

Pause

Unmute

Fullscreen
Now Playing









x
video of: How to Connect to WiFi on OPPO A15s // Establishing WiFi Network ConnectionPlay Video
How to Connect to WiFi on OPPO A15s // Establishing WiFi Network Connection

Share
Watch onHumix
How to Connect to WiFi on OPPO A15s // Establishing WiFi Network Connection
WIFI controlled car using Nodemcu circuit diagram
How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions


Step 4
OK, now glue the breadboard as follows. Then, attach the Nodemcu board to the breadboard.

How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

Step 5
Next, connect the motor driver board to the Nodemcu board. For that, use the above circuit diagram.

How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

Step 6
Now, connect the battery holder with the GND and 12v terminals on the motor drive board. After, glue it as follows.



How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

Step 7
OK. let’s set up the Blynk application. To do this. download and install this app on your smartphone using the App Store or Play Store. After, follow the steps below.

First, run the Blynk app on your smartphone. Then, click the “New project” button and enter the project name as you like. After, select the device and connection type. Finally, click the “Confirm” button.

How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions
OK, now we add to the widget interface. To do this, click the “+” button and add four “Styled buttons”. After, arrange them as follows.


How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

Now, let’s set up these buttons. First, click the up button and enter the button name as you like. After, change the PIN value to “virtual V0”. Change the edge type to “PILL” mode.
Second, click the down button and enter the button name as you like. After, change the PIN value to “virtual V1”. Change the edge type to “PILL” mode.
Third, click the left button and enter the button name as you like. After, change the PIN value to “virtual V2”. Change the edge type to “PILL” mode.
Last, click the right button and enter the button name as you like. After, change the PIN value to “virtual V3”. Change the edge type to “PILL” mode.



How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions
Then, we can see the buttons as follows.

Then, click again the “+” button and add a slider widget. After, click this widget and name it as you like. Change the PIN to “virtual V4”.

How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions

Lastly, arrange these buttons as follows.
How to make a WIFI controlled car using Nodemcu and Blynk app - Step by step instructions
Step 8
Next, connect this smart  car to the computer. OK. let’s now create the program for this smart car. It is as follows. First, download and install the libraries below.

WIFI Library — Download
Blynk Library — Download
The complete program of this project – Download
