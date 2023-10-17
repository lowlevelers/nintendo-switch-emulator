## Resources

- Nintendo Switch system software: https://en.wikipedia.org/wiki/Nintendo_Switch_system_software

Notable findings include that the Switch operating system is codenamed Horizon, that it is an evolution of the Nintendo 3DS system software, and that it implements a proprietary microkernel architecture.

## Other Emulators

- Ryujinx (MacOS / Linux / Windows): https://github.com/Ryujinx/Ryujinx

This breaks down the overall architecture of the NS, a good resource

- Yuzu (Linux / Windows): https://github.com/yuzu-emu/yuzu

## Tools

- radare2: https://github.com/radareorg/radare2

r2 is a complete rewrite of radare. It provides a set of libraries, tools and plugins to ease reverse engineering tasks. Distributed mostly under LGPLv3, each plugin can have different licenses (see r2 -L, rasm2 -L, ...).

- radare.book: https://book.rada.re/

Official guide book for Radare

- iaito: https://github.com/radareorg/iaito

Qt frontend for radare

- valgrind: https://valgrind.org/

Valgrind is an instrumentation framework for building dynamic analysis tools. There are Valgrind tools that can automatically detect many memory management and threading bugs, and profile your programs in detail. You can also use Valgrind to build new tools. (TLDR: Check memory allocation and debug memory leak in the low level environment)