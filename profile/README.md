# foliOS

An experimental operating system for AMD64, built around the Strata kernel. Strata keeps ordinary process isolation and adds a tier where signed drivers and services run beside the kernel, so they can skip process-style IPC when the ownership rules allow it.

The project is on hold. Development has moved to [Bedrock](https://bedrock-proj.github.io/).

[Site](https://foliOS-project.github.io/) · [Documentation](https://github.com/foliOS-project/foliOS/tree/main/docs)

| Repository | Contents |
| --- | --- |
| [foliOS](https://github.com/foliOS-project/foliOS) | Strata kernel, Vellum bootloader, documentation and design records |
| [foliSDK](https://github.com/foliOS-project/foliSDK) | Cross toolchain, C runtime, and build pipeline for the foliOS ABI |
| [sidlc](https://github.com/foliOS-project/sidlc) | Compiler for SIDL, the Strata interface definition language |
| [sma](https://github.com/foliOS-project/sma) | Archiver for signed kernel and user module images |
| [libstrata](https://github.com/foliOS-project/libstrata) | User-space C library for Strata handles |
| [Strata-sidl](https://github.com/foliOS-project/Strata-sidl), [foliOS-sidl](https://github.com/foliOS-project/foliOS-sidl) | SIDL interface definitions for the kernel and system services |

Toolchain ports: [gcc](https://github.com/foliOS-project/gcc-strata), [binutils](https://github.com/foliOS-project/binutils-strata), [musl](https://github.com/foliOS-project/musl-strata), [cmake](https://github.com/foliOS-project/cmake-strata), [autoconf](https://github.com/foliOS-project/autoconf-strata), [automake](https://github.com/foliOS-project/automake-strata), [libtool](https://github.com/foliOS-project/libtool-strata), [gnu-config](https://github.com/foliOS-project/gnu-config-strata).
