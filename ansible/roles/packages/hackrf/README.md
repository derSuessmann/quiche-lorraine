# libiio

This role installs libiio.

<!--more-->

> Library for interfacing with Linux IIO devices
>
> libiio is used to interface to the Linux Industrial Input/Output (IIO) Subsystem. The Linux IIO subsystem is intended to provide support for devices that in some sense are analog to digital or digital to analog converters (ADCs, DACs). This includes, but is not limited to ADCs, Accelerometers, Gyros, IMUs, Capacitance to Digital Converters (CDCs), Pressure Sensors, Color, Light and Proximity Sensors, Temperature Sensors, Magnetometers, DACs, DDS (Direct Digital Synthesis), PLLs (Phase Locked Loops), Variable/Programmable Gain Amplifiers (VGA, PGA), and RF transceivers. You can use libiio natively on an embedded Linux target (local mode), or use libiio to communicate remotely to that same target from a host Linux, Windows or MAC over USB or Ethernet or Serial.
> -- [libiio repository][1]

# Building

The build process is described in the [Wiki][2]. The role installs the required packages.

It follows the standard cmake build process. The role uses this.

# References

- [libiio repository][1] (last visited 2022-08-09)
- [README][2] (last visited 2022-08-09)

[1]: https://github.com/analogdevicesinc/libiio
[2]: https://wiki.analog.com/resources/tools-software/linux-software/libiio#how_to_build_it
