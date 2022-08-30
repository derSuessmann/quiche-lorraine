# CSDR

This role installs csdr.

<!--more-->

> `csdr` is a command line tool to carry out DSP tasks for Software Defined Radio.
>
> It can be used to build simple signal processing flow graphs, right from the command line.
>
>The included libcsdr library contains the DSP functions that csdr makes use of. It was designed to use auto-vectorization available in gcc, and also has some functions optimized with inline assembly for ARM NEON to achieve some speedup by taking advantage of SIMD command sets available in today's CPUs.
> -- [CSDR repository][1]

# Building

The build process is described in the [README][2]. The role installs the required packages.

It follows the standard cmake build process. The role uses this.

# References

- [CSDR repository][1] (last visited 2022-08-28)
- [README][2] (last visited 2022-08-28)

[1]: https://github.com/jketterl/csdr
[2]: https://github.com/jketterl/csdr/blob/develop/README.md
