# V-EZ

V-EZ is an open source, cross-platform (Windows and Linux) wrapper intended to alleviate the inherent complexity and application responsibility of using the Vulkan API. V-EZ attempts to bridge the gap between traditional graphics APIs and Vulkan by providing similar semantics to Vulkan while lowering the barrier to entry and providing an easier to use API.

<img src="https://github.com/GPGPU-Desigh-Agents/V-EZ/blob/master/Docs/img/VulkanAPI.PNG" />

<img src="https://github.com/GPGPU-Desigh-Agents/V-EZ/blob/master/Docs/img/V-EZ.PNG" />

## Documentation

The documentation for V-EZ can be found [here](https://gpuopen-librariesandsdks.github.io/V-EZ/)
## Prerequisites

* Windows 7, 8.1, 10 64-bit
* Linux 64-bit (tested on Fedora, Ubuntu)
* Visual Studio&reg; 2015 and later
* GCC 4.9 and later
* CMake 3.8 and later
* LunarG Vulkan SDK 1.1.70

## Hardware Support

V-EZ is not hardware vendor specific and should work on non-AMD hardware.

## Building V-EZ

- Run cmake to generate Visual Studio solution files or Linux make files.  No specific settings need to be set.

- Pull down submodules

`git submodule init`

`git submodule update`

- Build V-EZ project.
