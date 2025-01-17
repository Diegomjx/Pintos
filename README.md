# Pintos - Educational Operating System

Pintos is a simple educational operating system designed for teaching the fundamental concepts of operating systems development. This project was created to help students learn key aspects of operating systems such as process management, thread synchronization, memory management, and interrupt handling. Pintos is a low-level operating system written in C and assembly for the x86 architecture.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Running Pintos](#running-pintos)
- [Development and Contribution](#development-and-contribution)
- [Additional Documentation](#additional-documentation)
- [License](#license)

## Features

Pintos implements several key features of modern operating systems:

1. **Process Management**: Pintos supports process creation, termination, and management, and includes a priority-based process scheduler.
2. **Thread Synchronization**: Pintos includes support for threads, semaphores, and mutexes, enabling the development of concurrent applications.
3. **Memory Management**: Pintos implements basic memory management, including static and dynamic memory allocation and deallocation.
4. **File System**: The operating system includes a simple block-based file system.
5. **Interrupt Handling**: Pintos handles hardware interrupts for efficient interaction with the underlying hardware.
6. **Scheduling**: The scheduling system is priority-based, ensuring that higher-priority processes are executed first.

## Installation

To run Pintos in your development environment, you need to install a few dependencies and configure your system. The following steps outline how to install and set up Pintos.

### Prerequisites

- **Linux or macOS**: The operating system was developed to run in these environments.
- **GCC**: The C compiler used to build Pintos.
- **QEMU**: A hardware emulator to run Pintos in a virtualized environment.
- **Make**: The build tool used to compile the code.

### Installation Steps

1. Clone the Pintos repository:
   ```bash
   git clone https://github.com/your-username/pintos.git
   cd pintos
   ```
2. Install required dependencies (for Debian/Ubuntu-based systems):
   ```bash
   sudo apt-get update
   sudo apt-get install build-essential qemu
   ```
3. Configure the development environment:
   ```bash
   make
   ```
4. After the environment is set up, you can build Pintos by running:
   ```bash
   make
   ```

### Running Pintos
Once you've compiled Pintos, you can run it in an emulated environment using QEMU.
1. To start Pintos in the emulated environment with QEMU, run the following command:
   ```bash
   make qemu
   ```
2. To run Pintos with automated tests:
   ```bash
   make check
   ```

This will run a set of tests to verify that the various components of the operating system are functioning correctly.
