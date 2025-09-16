# Calypsi tool chains

Calypsi is a series of C compiler and assembly language cross compiler
tool chains. The current tool chains are aimed towards the
retro and hobby communities. Future products will be for typical
targets used in embedded programming.

## Supported targets and platforms

[Latest release is 5.12 available here for the following targets](https://github.com/hth313/Calypsi-tool-chains/releases/tag/5.12):

* MOS 6502
* WDC 65816
* Motorola 68000
* HP Nut (assembler and debugger only)

Supported host platforms are:

* Arch Linux, 64-bit x86
* Debian based Linux (built on Ubuntu 20.04), 64-bit x86
* Fedora based Linux (built on Fedora version 40), 64-bit x86 (except Nut target)
* macOS x86
* Windows 64-bit, built on Windows 10

## Highlights

* ISO C 99 compiler. This is a freestanding
  implementation with many features you will typically find in a
  hosted compiler.

* Fully re-entrant code model.

* Support for all integer types up to 64 bits `long long`.

* Floating point supported (32 and 64 bits IEEE-754).

* Full support for `struct`, `union`, `typedef` and what you
  expect to find in C.

* Support for (stack allocated) variable sized arrays.

* Optimizing compiler that can output source level debugging
  information.

* Source code debugger included.

* Support for ELF/DWARF, hex output as well as various target specific
  output formats.

## Allowed use

The tools are closed source. You can use them free of charge for
hobby purposes, which means you are not allowed to make your living
based on using the tools, either directly or indirectly.

Having a small side or hobby based income from using the Calypsi
tools is permitted.

An exception to the above is given to the HP-41 Nut target which is
provided with a BSD license to its binary distribution.
Permission is given to use the HP-41 Nut tools for commercial use,
free of charge.

## Feedback and issues

If you cannot find a suitable project below to post questions or
report issues in, feel free to do it in this
[project](https://github.com/hth313/Calypsi-tool-chains).

## Contact

If you feel need to reach me directly you can do so by sending
e-mail to hth313@gmail.com.

## Donations

A [donation](https://buymeacoffee.com/hth313) helps me work on this code
base and is very much appreciated.

## MOS 6502 target

The 6502 target supports the MOS6502, WDC65C02 and 45GS02 processors.

### Open source projects

* [Commodore](https://github.com/hth313/Calypsi-6502-Commodore) board support
  for Commodore 64 and MEGA65.

* [Hello World for Commodore 64](https://github.com/hth313/Calypsi-6502-hello-world)
  is a simple Hello World project which uses the board support as a submodule

* [On target debugger agent](https://github.com/hth313/Calypsi-remote-debug)

## WDC 65816 target

The 65816 target supports the WDC65816 processor.

### Open source projects

* [Foenix C256](https://github.com/hth313/Calypsi-65816-Foenix) board support
  for the C256U and FMX new retro computers. You can find more information
  about these computers at https://c256foenix.com

* [Hello World for C256U](https://github.com/hth313/Calypsi-65816-hello-world)
  is a simple Hello World project which uses the Foenix C256 board
  support as a submodule

* [Foenix F256](https://github.com/hth313/Calypsi-65816-F256) board support
  for the F256 and F256K retro computers. You can find more information
  about these computers at https://c256foenix.com

* [On target debugger agent](https://github.com/hth313/Calypsi-remote-debug)

## Motorola 68000 target

The 68000 target supports the Motorola 68000, 68020, 68040 processors.
There is also partial support for the APOLLO 68080 core.

### Open source projects

* [Amiga](https://github.com/hth313/Calypsi-Amiga) runtime support. This project
  is included with the product, but you can study the source code here and
  contribute to it.

* [Hello World for the Amiga](https://github.com/hth313/Calypsi-Amiga-hello-world)
  is a simple Hello World project for the Amiga.

* [Foenix A2560U/K](https://github.com/hth313/Calypsi-m68k-Foenix) board support
  for the A2560 new retro computers.
  This project is included with the product, but you can study the source code here
  and contribute to it.
  You can find more information about these computers at https://c256foenix.com

* [Hello World for A2560U](https://github.com/hth313/Calypsi-m68k-hello-world)
  is a simple Hello World project.

* [On target debugger agent](https://github.com/hth313/Calypsi-remote-debug)

## HP Nut target

The Nut target supports the HP-41 Nut and NEWT processors.

### Open source projects

* [OS4](https://github.com/hth313/OS4) is an extension module for the
  HP-41C operating system which greatly expands its capabilities

* [Ladybug](https://github.com/hth313/ladybug) is an HP-16C inspired
  module which makes use of the OS4 module to bring a HP-16C style
  calculator into the HP-41C

* [Boost41](https://github.com/hth313/boost41) provides user functions
  that is based on the features provided by the OS4 module
