# HamClock

This role installs HamClock. It provides nice clock with a world map for radio amateurs.

<!--more-->

> I thought it would be useful to build a desk clock that could show accurate time, geography, time zone, solar activity, sunrise and sunset times, Maidenhead locators, beam heading, Northern California DX Foundation (NCDXF) beacons, news headlines, and other timely information in one small device. Here’s how I assembled a 7-inch diagonal thin-film transistor (TFT) touchscreen color display, with a few embedded components to access all that data via Wi-Fi.
> -- Elwood Downey, WBØOEW in [QST October 2017][2]

HamClock started its life as an ESP8266 Arduino project. Later the author ported it to the Raspberry Pi or Linux in general. You can build and run it even on Windows and MacOS, if you really want to inflict pain to yourself.

# Building

I really do not understand, why so many hams provide their software as tarballs or even zip files. Elwood's HamClock is really a great piece of software. It annoys me just a little bit, that I had to use some trickery to determine the current version for my stow path.

The build process is described in the "Desktop" tabon the [web site][1]. Again, the web site has a strange UI, but is very informative.

The manual describes a rather simple build process: `make hamclock && sudo make install`. There are other targets `hamclock-big` alias `hamclock-1600x960`, `hamclock-2400x1440` and `hamclock-3200x1920`. `make install does not honor the prefix. Each build of a target deletes the old build files. This Ansible role implements therefore its own installation routines. It also build a tiny tool to extract the current version form the sources.

# References

- [HamClock site][1] (last visited 2021-07-25)
- [Original QST article proof][2] (last visited 2021-07-25)

[1]: https://www.clearskyinstitute.com/ham/HamClock/
[2]: https://www.clearskyinstitute.com/ham/HamClock/QST-HamClock.pdf