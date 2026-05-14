# PNZS2 - PlayStation 2 Emulator

A PlayStation 2 emulator built in C++ with support for Android 8.0 and above.

## Features

- **Android 8.0+ Support**: Optimized for Android devices running Android 8 (API level 26) or higher
- **Controller Support**: Full support for Android game controllers and input devices
- **Enhanced Graphics**: Optimized graphics rendering pipeline for mobile devices
- **PS2 Emulation**: Core PS2 console emulation including CPU, GPU, and memory management

## Requirements

- C++17 or later
- CMake 3.16+
- Android NDK (for Android builds)
- Android SDK (API level 26+)

## Building

### For Desktop (Linux/macOS/Windows)

```bash
mkdir build
cd build
cmake ..
make
