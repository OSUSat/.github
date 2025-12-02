# Open Source Utility Satellite
This organization is the home of all OSUSat hardware, software, libraries, and tooling.

# Repository Structure

- [cubesat](https://github.com/OSUSat/cubesat): this repository contains all of the hardware and firmware designs for our 4-subsystem climate science satellite
- [messaging](https://github.com/OSUSat/messaging): this repository is our messaging library for inter-subsystem communication and transmission to the ground. It exposes packet codecs & general enums/structures for use in applications that communicate with the system
- [core](https://github.com/OSUSat/core): this repository contains all of the basic primitives used in our embedded firmware. Things like ring buffers & event buses.
