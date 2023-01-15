# RubberDragonTrains Modpack

## Mods List
[The list of mods can be found here.][mods]

[Mods]: https://github.com/HazmatDrone/RubberDragonTrains/tree/master/.minecraft/mods


## Installation

### Prerequisites
1. Make sure you have [Java 17] installed first.
2. Download and install [Prism Launcher] (it will handle installing Minecraft and the mods for you)
3. During installation, set Java **17** as the default Java
4. Try to allocate about **8192MiB** of RAM at the minimum (your choice of max RAM)
5. Sign into your MS account via the Prism launcher


[Java 17]: https://aka.ms/download-jdk/microsoft-jdk-17.0.5-windows-x64.msi 
[Prism Launcher]: https://prismlauncher.org/download/

### Modpack (from zip)
1. [Download the modpack zip][modpack zip]
2. Drag the modpack zip file **directly** into the main window of the Prism Launcher (no extraction necessary)
3. Accept the Prism Launcher dialog to extract the files and install the modpack
4. Run the modpack

[Modpack zip]: https://github.com/HazmatDrone/RubberDragonTrains/archive/refs/tags/v1.1.zip


## Known Issues
This version of Create/Flywheel has some severe rendering issues on certain RX series cards on Windows. If you are experiencing crashes when trying to connect to the server or launch a world, follow these instructions:
1. Create a new superflat world and **disable structure generation**
2. Enter the command `/flywheel backend batching`
3. Try placing a chest. If your game crashes, repeat with a new world and instead use `/flywheel backend off`
4. Connect to the server.
