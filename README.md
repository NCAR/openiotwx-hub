## OpenIoTwx for Developers and Interested Parties

Welcome to the Hub repository for all projects falling within the openIoTwx umbrella.

At this point in time, no code or project files are hosted within this repo, as the purpose of it is to direct contributors and those interested to the sub-projects.

# openIoTwx Documentation Website

If you want to look further into our user documentation or ended up on the developer side of things by accident, check out our site:

* main website [https://ncar.github.io/openiotwx/](https://ncar.github.io/openiotwx/)

If you find a bug or would like to contribute to the source code of that site, please visit the repository, make some changes and a pull request:

* the source site repo: [https://github.com/NCAR/openiotwx](https://github.com/NCAR/openiotwx)

# 3D-Printed Design Files

If you want to look into our 3D design files, check out: 

* the STL file repo: [https://github.com/NCAR/openiotwx-stl](https://github.com/NCAR/openiotwx-stl)

# Supporting Software

There are two main components to the fully functioning system: MQTT Broker, the orchestrator and the CHORDS portal for real-time data display.

## MQTT Broker
The architecture requires MQTT to transmit data.  Any will do, but we have had the best experience with the open source [Mosquitto broker](https://mosquitto.org) maintained by Eclipse/IBM.

## Orchestrator
We only support full real-time data integration into [CHORDS](https://earthcubeprojects-chords.github.io/chords-docs/) and that is accomplished by If you want to look into the orchestrator that allows MQTT into our CHORDS instances, check out: 

* the source repo: [https://github.com/NCAR/chords-mqtt-orchestrator](https://github.com/NCAR/chords-mqtt-orchestrator)

## CHORDS Portal
If you need to set up a CHORDS instance, check out the project:

* the [CHORDS Portal](https://earthcubeprojects-chords.github.io/chords-docs/)

# Base Microcontroller Software

For access to the Arduino code and source code implementations, go to: 

* the base Arduino implementation which supports 7 sensors out of the box 
* the core source repo: [https://github.com/NCAR/esp32-atomlite-arduino-base](https://github.com/NCAR/esp32-atomlite-arduino-base)

# Contributors Wanted

We need help in the following areas:

* software development in Arduino and MicroPython
* documentation 
* in-field testing
* bug fixing
* 3D STL design for new sensors and improved housings


Contact us if you want to become part of this exciting project!