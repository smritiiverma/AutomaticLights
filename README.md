# Automatic Washroom Light README

This Arduino script is designed to control a washroom light automatically based on the number of people entering and exiting the room. The system uses two infrared sensors, one for detecting entry (`pin 7`) and the other for detecting exit (`pin 8`). The output pin (`pin 9`) controls the washroom light.

## Setup
1. Connect the entry sensor to `pin 7`.
2. Connect the exit sensor to `pin 8`.
3. Connect the light control output to `pin 9`.

## Operation
- The system increments the total count when someone enters and decrements when someone exits.
- The current occupancy is displayed using the Serial monitor.
- If there is at least one person in the washroom, the light (`pin 9`) is turned on; otherwise, it is turned off.

## How to Use
1. Upload this Arduino script to your Arduino board.
2. Open the Serial Monitor to view the current occupancy.
3. Connect the sensors and light according to the specified pins.

## Note
- Adjust the delay in the script (`delay(300)`) according to your preference.

Feel free to customize and enhance the code based on your specific requirements. If you encounter any issues or have suggestions, please create an issue on GitHub.

Happy automating!
