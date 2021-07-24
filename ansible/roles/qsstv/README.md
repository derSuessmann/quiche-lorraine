# QSSTV

This role installs QSSTV. It provides slow scan television (SSTV) and HAMDRM.


<!--more-->

The [QSSTV site][1] is quite horrible frame based, but the software works really well. The manual is quite comprehensive.

# Building

Strictly speaking could you live with the older version in the Raspberry Pi OS repositories, but the build is also not to difficult. 

The build process is described in the [manual][3]. The role installs the required packages without hamlib-dev. Hamlib is installed with the hamlib role.

The manual describes the build process with `qmake && make && sudo make install`. 

An issue might with QSSTV is that maintainer is seemingly only providing the current version as a downloadable tarball. The tarball even may change its structure. If the role does not work anymore, check this first.

# References

- [QSSTV site][1] (last visited 2021-07-24)
- [QSSTV manual][2] (last visited 2021-07-24)
- [QSSTV installation instruction][3] (last visited 2021-07-24)

[1]: http://users.telenet.be/on4qz/qsstv/index.html
[2]: http://users.telenet.be/on4qz/qsstv/manual/index.html
[3]: http://users.telenet.be/on4qz/qsstv/manual/installation.html