# Volk

This role installs VOLK.

> VOLK is a sub-project of GNU Radio. Please see http://libvolk.org for bug tracking, documentation, source code, and contact information about VOLK. See https://www.gnuradio.org/ for information about GNU Radio.
>
> VOLK is the Vector-Optimized Library of Kernels. It is a library that contains kernels of hand-written SIMD code for different mathematical operations. Since each SIMD architecture can be very different and no compiler has yet come along to handle vectorization properly or highly efficiently, VOLK approaches the problem differently.
>
>For each architecture or platform that a developer wishes to vectorize for, a new proto-kernel is added to VOLK. At runtime, VOLK will select the correct proto-kernel. In this way, the users of VOLK call a kernel for performing the operation that is platform/architecture agnostic. This allows us to write portable SIMD code.
> -- <cite>[VOLK readme in the git repository][1]</cite>

<!--more-->

# Building

The building process is described in the [Readme][1] in the project's git repository.

# Status

- [x] Build - completed without error
- [x] Software tests - completed without error

# References

- [VOLK repository][1] (last visited 2021-10-14)

[1]: https://github.com/gnuradio/volk.git
