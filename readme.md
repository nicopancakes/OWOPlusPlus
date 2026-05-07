## __This is an independent fork of SDR++. It is not the official SDR++ project and is not affiliated with, endorsed by, or otherwise connected to the SDR++ development team.__
# OWO++, The bloat-free SDR software

<img width="1144" height="910" alt="image" src="https://github.com/user-attachments/assets/05a91b6e-db97-4658-b6f5-3397c6a19276" />

OWO++ is a cross-platform, open-source SDR software focused on being lightweight, simple, and easy to use.

⚠ OWOPlusPlus is Still in Development!, Get OWOPlusPlus Lite **[Here.](https://github.com/nicopancakes/OWO-Lite)**

## SDR++ Discord
(Not affiliated with OWO++)

* [Discord Server](https://discord.gg/aFgWjyD)

## Features

* Multi VFO
* Wide hardware support (via SoapySDR and dedicated modules)
* SIMD-accelerated DSP
* Cross-platform (Windows, Linux, macOS, BSD)
* Full waterfall updates when possible for easier signal browsing
* Modular design (custom plugins supported)

---

# Installing

## Windows

Download the latest release from the Releases page or clone this repository and build from source.

> Note: The previous link was broken/mixed. Use either:
> - GitHub Releases page (if you publish releases), or
> - Source download (GitHub "Code → Download ZIP")

To create a desktop shortcut:
Right-click the executable → `Send to → Desktop (create shortcut)`, then rename it.

---

# Building on Windows

The preferred IDE is [VS Code](https://code.visualstudio.com/) using CMake.

## Dependencies

Install:

* cmake
* vcpkg
* PothosSDR (installs SDR hardware support libraries)
* RtAudio

Then via vcpkg:

* fftw3
* glfw3
* zstd
* libvolk

Use:
```bash
vcpkg install fftw3:x64-windows glfw3:x64-windows zstd:x64-windows libvolk:x64-windows
