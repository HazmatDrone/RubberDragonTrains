# RubberDragonTrains Modpack

## Mods List
[The list of mods can be found here.][mods]

[Mods]: https://github.com/HazmatDrone/RubberDragonTrains/tree/master/.minecraft/mods


## Installation

Follow the instructions to install from scratch at the [latest release].

[Latest release]: https://github.com/HazmatDrone/RubberDragonTrains/releases/latest/

## Known Issues
This version of Create/Flywheel has some severe rendering issues on certain RX series cards on Windows. If you are experiencing crashes when trying to connect to the server or launch a world, follow these instructions:
1. Create a new superflat world and **disable structure generation**
2. Enter the command `/flywheel backend batching`
3. Try placing a chest. If your game crashes, repeat with a new world and instead use `/flywheel backend off`
4. Connect to the server.
