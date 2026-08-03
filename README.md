# HyperLightOS-16

A hobby operating system written in **x86 Assembly (NASM)**.

HyperLightOS-16 is a BIOS-based 16-bit operating system developed from scratch for learning bootloaders, kernels, and operating system development.

## Features

* BIOS Bootloader
* 16-bit Real Mode Kernel
* Login Screen
* Desktop
* Start Menu
* Settings
* Oslo Shell
* Task Manager

## Requirements

* NASM 3.x
* QEMU 9.x or newer

## Building

```bash
cd project
build.bat
```

The build script assembles all source files into **os-image.bin** and starts QEMU.

## Project Structure

```
HyperLightOS-16/
│
├── project/
│   ├── boot.asm
│   ├── kernel.asm
│   ├── login.asm
│   ├── desktop.asm
│   ├── start.asm
│   ├── settings.asm
│   ├── oslo.asm
│   ├── taskmgr.asm
│   ├── build.bat
│   └── clean.bat
│
├── tools/
│   ├── nasm/
│   └── qemu/
│
├── README.md
├── LICENSE
└── .gitignore
```

## Roadmap

### Beta-1

* [x] Bootloader
* [x] Kernel
* [x] Login
* [x] Desktop
* [x] Start Menu
* [x] Settings
* [x] Oslo Shell
* [x] Task Manager

### Beta-2

* [ ] Application Launcher
* [ ] Improved Oslo Shell
* [ ] About Screen
* [ ] Shutdown Menu
* [ ] Memory Information

### Future

* [ ] Protected Mode
* [ ] FAT12 File System
* [ ] GUI
* [ ] Mouse Support
* [ ] File Explorer
* [ ] Text Editor
* [ ] Calculator
* [ ] Networking

## License

This project is licensed under the MIT License.
See the LICENSE file for details.

## Note: 
* This HyperLightOS is currently 16bit is currently HyperLightOS-16 which is 16bit, newer releases lik HyperLightOS-32 and HyperLightOS-64 willbe released after some update on HyperLightOS-16
* Can only be emulated using qemu 64bit and nasm 64bit currently
