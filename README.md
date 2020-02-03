# stranger-things
Hard-coded version of the Stranger Things Arduino code

[Link from ACM of McNeese email archive]
https://github.com/ErinBryson/IoST

## Setup Notes

[Notes pulled as-is from ACM of McNeese email archive]

Setting Up Arduino IDE with Adafruit Feather M0 WiFi
1) 	Download Arduino IDE 1.8 or higher.
	Use this link to the download page:
	https://www.arduino.cc/en/Main/Software

2) 	Extablish a connection to the required board libraries using this link:
	https://learn.adafruit.com/adafruit-feather-m0-wifi-atwinc1500/setup
	
3) 	Setup Arduino to use the board.
	Follow the directions on this page:
	https://learn.adafruit.com/adafruit-feather-m0-wifi-atwinc1500/using-with-arduino-ide

4) 	Install WiFi101 Library. 
	In the Arduino IDE go to Sketch>Include Library>Manage Libraries...

5) 	Repeat Step 4 for "Adafruit_GFX.h" and "Adafruit_SSD1306.h" libraries
		- GFX is for core graphics
		- SSD1306 is for the OLED Screen
		
6)  Download Adafruit_NeoPixel Library using the following link:
	https://learn.adafruit.com/adafruit-neopixel-uberguide/arduino-library-installation

Setting up Blynk
On Phone
1)  Navigate to the "Getting Started with Blynk" page using this link:
	https://www.blynk.cc/getting-started/
	
2) 	Download the Blynk app either on Android or iPhone, depending on your phone.
	This app is completely free and does not have ads, so don't worry about that!
	
3) Create an account with Blynk

4) Open the Blynk app and press select "New Project"

5) You should be greeted with this screen
	<INSERT PROJECT SETUP SCREENSHOT>
	
	a) Name your project!
	
	b) On "CHOOSE DEVICE" field, select "Arduino 101" as shown below
		<INSERT DEVICE SELECTION SCREENSHOT>
		
	c) 	On "CONNECTION TYPE" field, select "WiFi" as shown below
		<INSERT DEVICE SELECTION SCREENSHOT>
		
	d) 	Press "Create Project"
	
6)  You should now receive an email from Blynk with an authentication token. 
	You will need later, so either keep this email open or copy and paste the token somewhere.
	
7) Tap anywhere in the project background to open the "Widget Box" menu.

8)	Scroll down to the "DISPLAYS" section, then select "Terminal" as shown below
		<INSERT TERMINAL SELECTION SCREENSHOT>
		
9)	A Terminal widget will now be present in the project, as shown below
		<INSERT UPDATED PROJECT SCREENSHOT>

10) Tap on the Terminal widget to get this view
		<INSERT UPDATED PROJECT SCREENSHOT>
		
		a) Click on "PIN" to select the input. Select V1
		
		b) Keep "INPUT LINE" and "AUTO SCROLL" on
		
		c) Change the screen and text options however you like
		
		d) select "OK" and go to the next section

11) Go back to "Getting Started" webpage and click "DOWNLOAD BLYNK LIBrary"
		<Insert Screenshot>
		
12) Next click on the latest Blynk Release ZIP file, as shown below	
		<Insert Screenshot>

13) Extract the contents of the ZIP file into a folder. 
	
14)	Move the contents within "Library" into the Arduino>Libraries folder
	
15)	Move the "Tools" directory into the Arduino folder

Code
1) Open project in Arduino IDE

2) Go to line <INSERT LINE NUMBER HERE> and replace "Insert Token Here" with the token sent to you by Blynk

3) Insert your WiFi network name on line <INSERT LINE NUMBER HERE>

4)	Insert your WiFi network password on line <INSERT LINE NUMBER HERE>

5) Plug in the Adafruit Feather M0 WiFi Board using a Micro-USB to USB cable

6)	Select the correct Port your board is on as shown below	
		<INSERT SCREENSHOT>
		
OPERATING HARDWARE

