=================================
Supported Platforms
=================================

The core opendnp3 library is platform-neutral C++11.  It can target all major operating systems with a C++11 compiler and a number of bare-metal microcontrollers.

**Desktop/Server Operating Systems**

Operating system support is dependent on your C++11 compiler and the ASIO library support for your platform.

* Windows (MSVC++ & Visual Studio 2013 Express)
* Linux (GCC >= 4.7.3 or Clang >= 3.3)
* OSX (Clang >= 3.3)

**Embedded Linux**

The same Linux build has been used with a number of GCC-based ARM cross-compilers.
The example applications and unit tests will run on the Raspberry Pi and Beagle Bone Black.
These platforms are overkill, however, as the library will run on much more limited ARM-linux systems.

**Bare Metal**

If you are willing to write a Platform Abstraction Layer (PAL), opendnp3 will run on a microcontroller. 
The project includes Atmel Studio solution demos for the following targets.

* Arduino Mega (Atmega2560) - Uses ~50% of progmem and ~50% SRAM (pre-execution) - APDU buffer size reduced to 249 bytes, logging stripped
* Arduino Due (AT91SAM3X8E) - Uses ~30% of progmem and <10% of 96KB SRAM - No size reductions, logging intact