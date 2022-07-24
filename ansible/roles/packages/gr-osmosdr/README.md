# GNURadio

This role installs GNURadio.

> GNU Radio is a free & open-source software development toolkit that provides signal processing blocks to implement software radios. It can be used with readily-available low-cost external RF hardware to create software-defined radios, or without hardware in a simulation-like environment. It is widely used in research, industry, academia, government, and hobbyist environments to support both wireless communications research and real-world radio systems.
> -- <cite>[GNURadio project site][1]</cite>

<!--more-->

Raspberry Pi OS provides a version of GNURadio in the gnuradio package and could be installed with the package manager, but we want a more up-to-date version.

# Building

The building process is described in the [wiki article][3] on the project's web site. It follows the standard cmake build process. The role uses this.

# References

- [GNURadio project site][1] (last visited 2021-10-14)
- [GNURadio repository][2] (last visited 2021-10-14)
- [GNURadio wiki article][3] (last visited 2021-10-14)

[1]: https://www.gnuradio.org/
[2]: https://github.com/gqrx-sdr/gqrx.git
[3]: https://wiki.gnuradio.org/index.php/InstallingGRFromSource_on_Raspberry_Pi