# Dream

This role installs dream.

<!--more-->

> Dream is a software implementation of a Digital Radio Mondiale (DRM) receiver. With Dream, DRM broadcasts can be received with a modified analog receiver (SW, MW, LW) and a PC with a sound card.
> -- [Dream site][1]

# Building

The build process is described in the [OpenWebRX Wiki][2]. This Wiki describes the build process with `qmake && make && sudo make install`. 

An issue might with Dream is that the is not git repository and we are using a downloadable tarball. The tarball even may change its structure. If the role does not work anymore, check this first.

# References

- [Dream site][1] (last visited 2022-08-29)
- [OpenWebRX Wiki][2] (last visited 2022-08-29)

[1]: https://sourceforge.net/projects/drm/
[2]: https://github.com/jketterl/openwebrx/wiki/Manual-Package-installation-(including-digital-voice)
