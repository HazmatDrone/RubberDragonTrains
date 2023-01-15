# RubberDragonTrains Modpack

## Mods List
The list of mods can be found [here][mods]

## Installation

### Prerequisites
1. Make sure you have [Java 17] installed first.
2. Download and install [Prism Launcher]
3. During installation, set Java **17** as the default Java
4. Try to allocate about **8192MiB** of RAM at the minimum (your choice of max RAM)
5. Sign into your MS account via the Prism launcher

### Modpack
- [Instructions for installing and upgrading the modpack can be found here!][latest pack release]



[mods]: https://github.com/HazmatDrone/RubberDragonTrains/tree/master/.minecraft/mods

[Java 17]: https://aka.ms/download-jdk/microsoft-jdk-17.0.5-windows-x64.msi 
[Prism Launcher]: https://prismlauncher.org/download/

[Latest pack release]: https://github.com/HazmatDrone/RubberDragonTrains/releases/latest

## Known Issues
This version of Create/Flywheel has some severe rendering issues on certain RX series cards on Windows. If you are experiencing crashes when trying to connect to the server or launch a world, follow these instructions:
1. Create a new superflat world and **disable structure generation**
2. Enter the command `/flywheel backend batching`
3. Try placing a chest. If your game crashes, repeat with a new world and instead use `/flywheel backend off`
4. Connect to the server.
