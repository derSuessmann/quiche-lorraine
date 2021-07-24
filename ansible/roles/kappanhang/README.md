# kappanhang

This role installs kappanhang. kappanhang is a nice terminal programm for remotely operating some ICOM transceivers.


<!--more-->

> kappanhang remotely opens audio channels and a serial port to an Icom RS-BA1 server. The app is mainly developed for connecting to the Icom IC-705 transceiver, which has built-in Wi-Fi and RS-BA1 server. All features of the protocol are implemented including packet retransmission on packet loss.
> -- <cite>[Kappanhang project][1]</cite>

# Building

The build process is described in the [README.md file][2]. The problem for the Quiche-Lorraine project was building a specific version of the programm. The standard `go get <repo>@<version>` did not work with the tag `v1.3`. The reason might be that `go get` expects a specific format. The issue has been solved by using the commit hash. The intended commit must be set in the variable `git_commit`. The `version` variable should be set to the ISO date of the commit.

# References

- [Kappanhang project site][1] (last visited 2021-07-24)
- [README.md][2] (last visited 2021-07-24)

[1]: https://github.com/nonoo/kappanhang
[2]: https://github.com/nonoo/kappanhang/blob/main/README.md