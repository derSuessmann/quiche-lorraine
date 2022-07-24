# Gqrx  SDR for the Raspberry Pi

This role installs Gqrx.

> Gqrx is an open source software defined radio receiver (SDR) powered by the GNU Radio and the Qt graphical toolkit.
> -- <cite>[Gqrx project site][1]</cite>

<!--more-->

Raspberry Pi OS provides a version of gqrx in the gqrx-sdr package and could be installed with the package manager, but we want a more up-to-date version.

# Building

The building process is described in the [blog article][3] on the project's web site. It follows the standard cmake build process. The role uses this.

# References

- [Gqrx project site][1] (last visited 2021-10-14)
- [Gqrx repository][2] (last visited 2021-10-14)
- [Gqrx blog article][3] (last visited 2021-10-14)

[1]: https://gqrx.dk/
[2]: https://github.com/gqrx-sdr/gqrx.git
[3]: https://gqrx.dk/download/gqrx-sdr-for-the-raspberry-pi