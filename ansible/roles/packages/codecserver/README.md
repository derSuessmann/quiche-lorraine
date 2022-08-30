# Codec server

This role installs codecserver.

<!--more-->

> The Codec Server will coordinate central dispatching and coordination of (hardware or software) codecs over the network.
>
> The network stack is connection-oriented, and runs on Unix domain sockets or TCP over IPv4 or IPv6.
>
> It uses a protocol based on protocol buffers (or protobuf for short) to communicate, exchanging length-delimited Any-encapsulated messages on the sockets.
>
> The codec system is modular, and can be extended with custom drivers and modules. The base package comes with the ambe3k driver to interface with AMBE-3000 devices over a serial interface.
>
> The primary use case for this application is to allow decoding of AMBE-based digital voice modes in the OpenWebRX project, but the basic design has been kept neutral so it can be used in other applications as well.
> -- [Repository][1]

# Building

The build process is described in the [README][2]. The role installs the required packages.

It follows the standard cmake build process. The role uses this.

# References

- [Repository][1] (last visited 2022-08-28)
- [README][2] (last visited 2022-08-28)

[1]: https://github.com/jketterl/codecserver
[2]: https://github.com/jketterl/codecserver/blob/develop/README.md
