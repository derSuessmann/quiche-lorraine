# USRP Hardware Driver (UHD)

This role installs UHD. GNURadio can use USRP SDR products, but it needs the UHD. This role can be added as a dependency to GNURadio, if USRP SDR products may be used. 

> The USRP Hardware Driver™ (UHD) software API supports application development on all USRP SDR products. Using a common software interface is critical as it increases code portability, allowing applications to transition seamlessly to other USRP SDR platforms when development requirements expand or new platforms are available. Hence, it enables a significant reduction in development effort by allowing you to preserve and reuse your legacy code so you can focus on new algorithms. For more detailed information please visit our knowledge-based article on UHD.
>
>UHD also offers cross-platform support for multiple industry standard development environments and frameworks, including RFNoC, GNU Radio, LabVIEW and Matlab/Simulink. And to ensure you have no restrictions on how you use UHD, it is available on Linux, Windows, and Mac OS.
> -- <cite>[UHD project site][1]</cite>

<!--more-->

# Building

The building process is described in the [wiki article][3] on the project's web site, but it is rather complicated as it shows instruction for different Linux distributions. We use the build instructions from the [GNURadio site][4]. The build process uses `cmake`. The role does not use the `cmake_build_install` task, because the `CMakeLists.txt` configuration file is to be found in the `host` subdirectory of the project's git repository.

# Status

- [x] Build - completed without error
- [x] Software tests - completed without error
- [ ] Tested with hardware - no hardware available

# References

- [UHD project site][1] (last visited 2021-10-14)
- [UHD repository][2] (last visited 2021-10-14)
- [Building and Installing the USRP Open-Source Toolchain (UHD and GNU Radio) on Linux][4] (last visited 2021-10-14)
- [GNURadio installation on Raspberry Pi article][3] (last visited 2021-10-14)

[1]: https://www.ettus.com/sdr-software/uhd-usrp-hardware-driver/
[2]: https://github.com/EttusResearch/uhd.git
[3]: https://kb.ettus.com/Building_and_Installing_the_USRP_Open-Source_Toolchain_(UHD_and_GNU_Radio)_on_Linux
[4]: https://wiki.gnuradio.org/index.php/InstallingGRFromSource_on_Raspberry_Pi
