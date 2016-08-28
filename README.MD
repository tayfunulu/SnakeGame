Raspberry Pi + 8*8 RGB LED MATRIX DEMO 
=====================================

Just a sample python code. 

  Youtube : https://youtu.be/qAIZFgBWhSc

You have to install libary of rpi_ws281x wriiten by Jeremy Garff

  Libary : https://github.com/jgarff/rpi_ws281x

## Usage

  - Firstly you have to setup libary (rpi_ws281x) 
  - To be sure that it's working  with sudo ./test
  - I had a problem with Raspberry pi 3 , i added these lines on /boot/config.txt file and problem was solved after reboot

				hdmi_force_hotplug=1
				hdmi_force_edid_audio=1

	- to download a game

				git clone https://github.com/tayfunulu/SnakeGame.git

	- to run a code you need super user right. 
	
				cd SnakeGame
				sudo python snake.py 
	
-	To Play, in terminal you could use arrow keys 
-	Enjoy :) 
