# Calypsi tool chains

Calypsi is a series of C compiler and assembly language cross compiler
tool chains. The current tool chains are aimed towards the
retro and hobby communities. Future products will be for typical
targets used in embedded programming.

## Feedback and issues

If you cannot find a suitable project below to post questions or
report issues in, feel free to do it in this project.

## Allowed use

The tools are closed source and the long term goal is to provide
quality tools for commercial use. You can use them free of charge for
hobby purposes, which very roughly means you or not making a living
based on using the tools, either directly or indirectly.

If you do make your living based on these products then you can buy a
license.

## Highlights

* ISO C 99 compiler. This is a freestanding
  implementation with many features you will typically find in a
  hosted compiler.

* Fully reentrant code model.

* Support for all integer types up to 64 bits `long long`.

* Floating point supported (32 and 64 bits IEEE-754).

* Full support for struct, union, typedef and what you expect to
  find in C.

* Support for (stack allocated) variable sized arrays.

* Optimizing compiler that can output source level debugging
  information.

* Source code debugger included.

* Support for ELF/DWARF, hex output as well as various target specific
  output formats.

## MOS 6502 target

The 6502 target supports the MOS6502 and WDC65C02 processors.

### Open source projects

* [Commodore 64](https://github.com/hth313/Calypsi-6502-Commodore) board support

* [Hello World for Commodore 64](https://github.com/hth313/Calypsi-6502-hello-world)
  is a simple Hello World project which uses the board support as a submodule

* [On target debugger agent](https://github.com/hth313/Calypsi-remote-debug)

### Downloads

You can find the [current user guide here](https://tinyurl.com/28wpxn88).

Installers are available for some common 64 bit operating systems.

* [Arch Linux amd64](https://tinyurl.com/2xesvt5p)

* [Debian Linux amd64](https://tinyurl.com/e2auuf8f)

* [macOS](https://tinyurl.com/am72pz5j)

* [Windows](https://tinyurl.com/jjt2ysjx)


## WDC 65816 target

The 65816 target supports the WDC65816 processor.

### Open source projects

* [Foenix C256](https://github.com/hth313/Calypsi-65816-Foenix) board support
  for the C256U and FMX new retro computers. You can find more information
  about these computers at https://c256foenix.com

* [Hello World for C256U](https://github.com/hth313/Calypsi-65816-hello-world)
  is a simple Hello World project which uses the Foenix C256 board
  support as a submodule

* [On target debugger agent](https://github.com/hth313/Calypsi-remote-debug)

### Downloads

You can find the [current user guide here](https://tinyurl.com/5n98f4r2).

Installers are available for some common 64 bit operating systems.

* [Arch Linux amd64](https://tinyurl.com/5n88wfn6)

* [Debian Linux amd64](https://tinyurl.com/2p8av29n)

* [macOS](https://tinyurl.com/mwt3dxzc)

* [Windows](https://tinyurl.com/2p98hnum)

## Motorola 68000 target

The 68000 target supports the Motorola 68000 processor.

### Open source projects

* [Foenix A2560U/K](https://github.com/hth313/Calypsi-m68k-Foenix) board support
  for the C256U and FMX new retro computers. You can find more information
  about these computers at https://c256foenix.com

* [Hello World for A2560U](https://github.com/hth313/Calypsi-m68k-hello-world)
  is a simple Hello World project which uses the Foenix A2560U board
  support as a submodule

* [On target debugger agent](https://github.com/hth313/Calypsi-remote-debug)

### Downloads

You can find the [current user guide here](https://tinyurl.com/bde4uspb).

Installers are available for some common 64 bit operating systems.

* [Arch Linux amd64](https://tinyurl.com/b3ear55p)

* [Debian Linux amd64](https://tinyurl.com/yrrrrp3f)

* [macOS](https://tinyurl.com/3v9jjktc)

* [Windows](https://tinyurl.com/3kfbxx5v)

## HP Nut target

The Nut target supports the HP-41 Nut and NEWT processors.

### Open source projects

* [OS4](https://github.com/hth313/OS4) is an extension module for the
  HP-41C operating system which greatly expands its capabilities

* [Ladybug](https://github.com/hth313/ladybug)is an HP-16C inspired
  module which makes use of the OS4 module to bring a HP-16C style
  calculator into the HP-41C

* [Boost41](https://github.com/hth313/boost41) provides user functions
  that is based on the features provided by the OS4 module

### Downloads

You can find the [current user guide here](https://tinyurl.com/4bfck4u9)
and the separate [debugger user guide here](https://tinyurl.com/2p82yjjt]).

Installers are available for some common 64 bit operating systems.

* [Arch Linux amd64](https://tinyurl.com/ycks3unh)

* [Debian Linux amd64](https://tinyurl.com/2p8294ct)

* [macOS](https://tinyurl.com/4xb5eprb)

* [Windows](https://tinyurl.com/3v4nn34m)
