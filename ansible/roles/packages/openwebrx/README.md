# OpenWebRX

This role installs openwebrx.

<!--more-->

> OpenWebRX is a multi-user SDR receiver software with a web interface.
>
> It has the following features:
>
> - csdr based demodulators (AM/FM/SSB/CW/BPSK31/BPSK63)
> - filter passband can be set from GUI
> - it extensively uses HTML5 features like WebSocket, Web Audio API, and Canvas
> - it works in Google Chrome, Chromium and Mozilla Firefox
> - supports a wide range of SDR hardware
> - Multiple SDR devices can be used simultaneously
> - digiham based demodularors (DMR, YSF, Pocsag, D-Star, NXDN)
> - wsjt-x based demodulators (FT8, FT4, WSPR, JT65, JT9, FST4, FST4W)
> - direwolf based demodulation of APRS packets
> - JS8Call support
> - DRM support
> - FreeDV support
> - M17 support based on m17-cxx-demod
> -- [OpenWebRX repository][1]

# Building

The build process is described in the [Wiki][2]. The role installs the required packages.

It follows the standard cmake build process. The role uses this.

# References

- [OpenWebRX repository][1] (last visited 2022-08-24)
- [README][2] (last visited 2022-08-24)

[1]: https://github.com/jketterl/openwebrx
[2]: https://github.com/jketterl/openwebrx/wiki/Manual-Package-installation-(including-digital-voice)
