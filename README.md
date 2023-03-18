# Autonomous Remote Control Pickup Script for Space Engineers
This script is designed for a remote control flying vehicle in the space exploration game "Space Engineers". The script allows the player to request a pickup and the vehicle will autonomously fly to the player's location and hover above them.

# Setup
To use this script, you will need to have a remote control block and a radio antenna block on the flying vehicle. Additionally, the "IncreaseAltitude" action needs to be assigned to a control on the remote control block in the game's control panel.

# Installation
- Copy the code from the script file.
- In Space Engineers, go to the Programming block and click "Edit".
- Paste the code into the editor and save the script.
- Rename the script to something memorable (e.g. "RemoteControlPickup").
- Exit the Programming block and find your remote control block and radio antenna block in the game world.
- Rename them to "Remote Control" and "Antenna" respectively (or modify the code to match your block names).
- Go back to the Programming block and run the script by passing the argument "request_pickup" to the Main method.
# Usage
To use the script, simply run the program with the argument "request_pickup" in the game's Programming block. The script will find the nearest player and fly to their location, hovering 200 meters above them. If there are any obstacles between the vehicle and the hover position, it will adjust its position to avoid them.

# Customization
The script can be customized by modifying the HoverAltitude and RaycastDistance constants to suit your needs. Additionally, you can modify the script to add additional functionality or change the behavior of the vehicle.

# Notes
Make sure that the flying vehicle has enough power and fuel to make the trip to the player's location and hover for an extended period of time.
If the vehicle does not have enough power or fuel, it may crash or fall out of the sky while attempting to hover.
