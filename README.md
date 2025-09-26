# SkySnare
These are all artifacts from the Rincon Research Corporation's 2024 summer internship program in Tucson, which ran 10 weeks from May 28th - August 2nd.

When beginning the internship, we were given the general instructions to make a system to track drones via Remote ID and some initial components to try to accomplish that task. We ended up completing our initial system with one large station on week 4 and moved on to constructing smaller tracking nodes to address some issues with the range of our initial system as well as making many UI features.

# Project description
Skysnare is a drone tracking system that consists of:
- a station with an omnidirectional antenna, directional antenna and camera that get pointed at the drone in flight
- smaller nodes that extend the range of the base larger station
- a web application that allows for monitoring of an area via a map and for the system to be controlled remotely

Below is a video of the larger station tracking a drone as it flies in front of it.


https://github.com/user-attachments/assets/bb05e158-56e7-4068-bc9c-90517a4a683b


The system tracks the drones by utilizing Remote ID, a standard by the FAA requiring drones to broadcast their location via bluetooth and wifi as they are in flight.

Here is a demo of the playback mode utilizing data from the test seen above:

https://github.com/user-attachments/assets/1b6b7ded-23c2-4e7e-af90-677b6f6f6a79

# My work
Built the developer space by kickstarting machines, configuring user accounts, and verifying network connections.
Developed the "geo-fenching feature" which is not shown in the demo but allows users

Forked from Jacob Hunter's Github Project that contained all of the publically available files from the project.
