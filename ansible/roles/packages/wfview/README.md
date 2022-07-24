# wfview

This role installs wfview. wfview is a is a nice GUI programm for remotely operating some ICOM transceivers.


<!--more-->

> wfview is open-source software for the control of modern Icom radios, including the IC-7300, IC-7610, IC-705, IC-R8600 and IC-9700. USB and LAN are supported. See wfview.org
> -- [wfview repository][2]

# Building

The build process is described in the [INSTALL.md][3]. The role installs the required packages.

The manual describes the build process with `qmake && make && sudo ./install.sh`. This does not work, if the installation path differs from the default on Linux. The code has been fixed for this in [my repository on Gitlab][4]. A merge request has been posted.

# References

- [wfview web site][1] (last visited 2021-07-24)
- [wfview repository][2] (last visited 2021-07-24)
- [Installation instructions][3] (last visited 2021-07-24)

[1]: https://wfview.org/
[2]: https://gitlab.com/eliggett/wfview
[3]: https://gitlab.com/eliggett/wfview/-/blob/master/INSTALL.md
[4]: https://gitlab.com/derSuessmann/wfview