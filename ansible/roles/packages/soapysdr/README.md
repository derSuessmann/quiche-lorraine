# SoapySDR

This role installs SoapySDR.

<!--more-->

> SoapySDR is an open-source generalized API and runtime library for interfacing with SDR devices. With SoapySDR, you can instantiate, configure, and stream with an SDR device in a variety of environments. Most off the shelf SDR hardware platforms are supported by SoapySDR, and many open source applications rely on SoapySDR for hardware integration support. In additon, SoapySDR has bindings for development frameworks like GNU Radio and Pothos.
> -- [SoapySDR wiki][1]

# Building

The build process is described in the [wiki][3]. The role installs the required packages.

The build is based on cmake.

The stowing of this package is a bit tricky. The issues start with the Python site-packages directory, which is called dist-packages on Debian... Another issue is the folder for the modules of SoapySDR. Currently, the modules like soapyrtlsdr is installed by roles inside this role. This works with a small hack.

# References

- [SoapySDR wiki][1] (last visited 2022-06-26)
- [SoapySDR repository][2] (last visited 2022-06-26)
- [Installation instructions][3] (last visited 2022-06-26)

[1]: https://github.com/pothosware/SoapySDR/wiki
[2]: https://github.com/pothosware/SoapySDR
[3]: https://github.com/pothosware/SoapySDR/wiki/BuildGuide
