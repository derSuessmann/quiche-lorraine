# wxWidgets

This role installs wxWidgets. 
<!--more-->

> wxWidgets is a free and open source cross-platform C++ framework for writing advanced GUI applications using native controls.
>
> wxWidgets allows you to write native-looking GUI applications for all the major desktop platforms and also helps with abstracting the differences in the non-GUI aspects between them. It is free for the use in both open source and commercial applications, comes with the full, easy to read and modify, source and extensive documentation and a collection of more than a hundred examples. You can learn more about wxWidgets at https://www.wxwidgets.org/ and read its documentation online at https://docs.wxwidgets.org/
> -- [wxWidgets web site][1]

The CubicSDR build from source requires a static wxWidgets library. The role builds it.

# Building

The build process is described in the [README.md][3]. The role installs the required packages. 

The build process is a standard autoconf build. No bells or whistles, clean and working perfect with the prefix. I had issues with the installation of gtk. The build failed because the pkg-config was not found.After reinstalling `libgtk-3-dev` the build succeeded.

# References

- [liquid-dsp web site][1] (last visited 2021-10-22)
- [liquid-dsp repository][2] (last visited 2021-10-22)
- [README.md][3] (last visited 2021-10-22)

[1]: https://liquidsdr.org/
[2]: https://github.com/jgaeddert/liquid-dsp
[3]: https://github.com/jgaeddert/liquid-dsp/README.md
