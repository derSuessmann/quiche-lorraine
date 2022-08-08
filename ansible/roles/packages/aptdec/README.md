# Aptdec

This role installs Aptdec.

<!--more-->

> Aptdec is a FOSS program that decodes images transmitted by NOAA weather satellites. These satellites transmit constantly (among other things) medium resolution (4km/px) images of the earth over a analog mode called APT. These transmissions can easily be received with a cheap SDR and simple antenna. Then the transmission can be decoded in narrow FM mode.
> -- [Aptdec repository][1]

# Building

The build process is described in the [README][2]. The role installs the required packages.

It follows the standard cmake build process. The role uses this.

# References

- [Aptdec repository][1] (last visited 2022-08-07)
- [README][2] (last visited 2022-08-07)

[1]: https://github.com/Xerbo/aptdec
[2]: https://github.com/Xerbo/aptdec/blob/master/README.md
