# Automatic Washroom Light README

This script controlsthe lights in a room automatically based on how many people are going in and out.It uses two special sensors:one for when someone enters the room(connected to 'pin 7'), and another for when someone exits (connected to 'pin 8').
The output, which controls the light, is connected to 'pin 9'.

# Setting it up
1. Connect th sensor for people entering the room to `pin 7`.
2. Connect the sesnor for people exiting the room to `pin 8`.
3. Connect the light control to 'pin 9'

## How It works
- When someone enters the room, the system adds one to the count of people in the room.
- When someone leaves, it substracts one from the count.
- You can see how many people are in the room by looking at the Serial Monitor on your computer.
- If there's at least one person in the room, the light connected to 'pin 9' turn on. Otherwise it turns off.


## How to Use It
1. Put this script on your Arduino board.
2. Open the Serial Monitor to check how many people are in the room.
3. Make sure to connect the sensors and the light according to the pins we mentioned.

## Helful Tip
- You can change the 'delay(300)' in the script to make it work at a different speed if you want.
  Feel free to make this system work the way you want it to.If you run into any problems or have ideas for improvements.

  Enjoy your automated light system!
