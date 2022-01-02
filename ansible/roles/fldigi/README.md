# Fldigi

This role installs fldigi.

<!--more-->

> Fldigi (short for Fast light digital) is a free and open-source program which allows an ordinary computer's sound card to be used as a simple two-way data modem. The software is mostly used by amateur radio operators who connect the microphone and headphone connections of an amateur radio SSB or FM transceiver to the computer's headphone and microphone connections, respectively.
> This interconnection creates a "sound card defined radio" whose available bandwidth is limited by the sound card's sample rate and the external radio's bandwidth.
> Such communications are normally done on the shortwave amateur radio bands in modes such as PSK31, MFSK, RTTY, Olivia, and CW (Morse code). Increasingly, the software is also being used for data on VHF and UHF frequencies using faster modes such as 8-PSK.
> Using this software, it is possible for amateur radio operators to communicate worldwide while using only a few watts of RF power. 
> -- [Wikipedia article][4]

# Building

The build process is described in the [installation instructions][3]. There is also an `INSTALL` file in the source tarball. The role installs the required packages.

It follows the standard `configure && make && make install` process. The role uses this.

# References

- [W1HKJ web site][1] (last visited 2022-01-01)
- [Fldigi manual][2] (last visited 2022-01-01)
- [Installation instructions][3] (last visited 2022-01-01)
- [Wikipedia article][4] (last visited 2022-01-01)

[1]: http://www.w1hkj.com/
[2]: http://www.w1hkj.com/FldigiHelp/index.html
[3]: https://sourceforge.net/p/fldigi/wiki/debian_howto/
[4]: https://en.wikipedia.org/wiki/Fldigi