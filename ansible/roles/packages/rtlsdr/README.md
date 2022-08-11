# rtl-sdr

This role installs rtl-sdr.

<!--more-->

> DVB-T dongles based on the Realtek RTL2832U can be used as a cheap SDR, since the chip allows transferring the raw I/Q samples to the host, which is officially used for DAB/DAB+/FM demodulation. The possibility of this has been discovered by Eric Fry (History and Discovery of RTLSDR). Antti Palosaari has not been involved in development of rtl-sdr.
> -- [rtl-sdr repository][1]

# Building

The build process is described in the [Wiki][2]. The role installs the required packages.

It follows the standard cmake build process. The role uses this.

# References

- [rtl-sdr repository][1] (last visited 2022-08-08)
- [README][2] (last visited 2022-08-08)

[1]: https://gitea.osmocom.org/sdr/rtl-sdr
[2]: https://osmocom.org/projects/rtl-sdr/wiki
