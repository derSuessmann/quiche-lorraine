# Fllog

This role installs fllog.

<!--more-->

> The logbook server maintains a large set of QSO logbook fields that will probably be sufficient for casual operating, contesting and some certificate logging. All of the fields that are captured in the logbook are maintained in an ADIF database that can be read by any logbook program that can read the ADIF text format. The server can open any logbook adif file, including those created by fldigi.
> -- [Fllog manual][2]

# Building

The build process is described in `INSTALL` file in the source tarball. The role installs the required packages.

It follows the standard `configure && make && make install` process. The role uses this.

# References

- [W1HKJ web site][1] (last visited 2022-01-01)
- [Fllog manual][2] (last visited 2022-01-01)

[1]: http://www.w1hkj.com/
[2]: http://www.w1hkj.com/fllog-help/
