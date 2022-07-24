# Ham Radio Control Library - Hamlib

This role installs a specified version of the hamlib. Hamlib provides some tools and an API for controlling different transceivers.

<!--more-->

> Welcome to Hamlib!
>
>The Ham Radio Control Library–Hamlib, for short–is a project to provide programs with a consistent Application Programming Interface (API) for controlling the myriad of radios and rotators available to amateur radio and communications users.
> -- <cite>[Hamlib project site][1]</cite>

Raspberry Pi OS provides a version of hamlib and could be installed with the package manager, but we want a more up-to-date version.

# Building

The building process is described in the [README file][3] in the project's sources. It follows the standard `./configure && make && make install`. The role uses this.

# References

- [Hamlib project site][1] (last visited 2021-07-24)
- [Hamlib repository][2] (last visited 2021-07-24)
- [Hamlib Readme][3] (last visited 2021-07-24)

[1]: https://hamlib.github.io/
[2]: https://github.com/Hamlib/Hamlib
[3]: https://github.com/Hamlib/Hamlib/blob/master/README