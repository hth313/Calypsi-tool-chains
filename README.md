# Calypsi tool chains

Calypsi is a series of C compiler and assembly language cross compiler
tool chains. The current tool chains are aimed towards the
retro and hobby communities. Future products will be for typical
targets used in embedded programming.

## News, recent releases

### 3.6.2 April 2022

* Simplified linker files.

* Source debugging on target (68000)

* Semi-hosted support. Allows the debugger to provide streams, file
  system and assert functionality to a program being debugged if the
  target system lacks such abilities.

### 3.5.1 January, 2022

* 68000 tool chain added.

* Windows supported platform.

* Source debugging on target (65816)

* Full 64 bit floating point support.

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

Donations to help me work on this code base is very much appreciated.
If you feel that you want to help you can do so by using Paypal to
hth313@gmail.com. This is by no means mandatory, you are free to use
the tools regardless, as mentioned above.

Currently I am hoping to raise money towards a new Mac laptop as the
current one being used is 7 years old. Long term support on macOs of
these tools relies on this.

## MOS 6502 target

The 6502 target supports the MOS6502 and WDC65C02 processors.

### Open source projects

* [Commodore 64](https://github.com/hth313/Calypsi-6502-Commodore) board support

* [Hello World for Commodore 64](https://github.com/hth313/Calypsi-6502-hello-world)
  is a simple Hello World project which uses the board support as a submodule

* [On target debugger agent](https://github.com/hth313/Calypsi-remote-debug)

### Downloads

You can find the [current user guide here](https://tinyurl.com/mw8rfzb5).

Installers are available for some common 64 bit operating systems.

* [Arch Linux amd64](https://tinyurl.com/78pvpvyn)

* [Debian Linux amd64](https://tinyurl.com/mtsd6cbx)

* [macOS](https://tinyurl.com/75rbdjx7)

* [Windows](https://tinyurl.com/2p874whz)


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

You can find the [current user guide here](https://tinyurl.com/2p8np9ds).

Installers are available for some common 64 bit operating systems.

* [Arch Linux amd64](https://tinyurl.com/ywdwpfxx)

* [Debian Linux amd64](https://tinyurl.com/5n8avva5)

* [macOS](https://tinyurl.com/2p9y7s7x)

* [Windows](https://tinyurl.com/2p92dwyh)

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

You can find the [current user guide here](https://tinyurl.com/y2bs57t2).

Installers are available for some common 64 bit operating systems.

* [Arch Linux amd64](https://tinyurl.com/2p86vynr)

* [Debian Linux amd64](https://tinyurl.com/mum96v3f)

* [macOS](https://tinyurl.com/296pjbvp)

* [Windows](https://tinyurl.com/yup8b2bc)

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

You can find the [current tools user guide here](https://tinyurl.com/2tfym4ja)
and the separate [debugger user guide here](https://tinyurl.com/3h9hmksy).

Installers are available for some common 64 bit operating systems.

* [Arch Linux amd64](https://tinyurl.com/c2yrauey)

* [Debian Linux amd64](https://tinyurl.com/2p9hbus5)

* [macOS](https://tinyurl.com/4fdhr23b)

* [Windows](https://tinyurl.com/29ruk4np)
