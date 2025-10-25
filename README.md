Typing Speed Test
A professional-grade typing speed test application developed in C using the raylib graphics library, designed to help users improve typing speed and accuracy across multiple text modes.

Features
Three Modes:

Code snippets

Standard sentences

Sprint word groups

Real-Time Input Capture: Monitor typing progress live

Performance Metrics: Words Per Minute (WPM) and accuracy percentage

Detailed Results: Speed, accuracy, words typed, and elapsed time

Simple and Interactive UI: Powered by raylib for smooth cross-platform graphics

Prerequisites
Ensure the following tools and libraries are installed on your system:

C compiler: GCC, Clang, or MSVC with C11 support

raylib graphics library: For rendering

CMake: Version 3.10 or above for build configuration

Installing raylib
Install raylib by running the appropriate command for your platform:

bash
# Debian/Ubuntu
sudo apt install libraylib-dev
bash
# Fedora
sudo dnf install raylib-devel
bash
# macOS (Homebrew)
brew install raylib
For Windows, use vcpkg or download prebuilt binaries from the raylib website.

Build and Run Instructions
To build and execute the project, use the following commands in your terminal or command prompt:

bash
# Clone the GitHub repository
git clone https://github.com/yourusername/TypingSpeedTest.git
cd TypingSpeedTest

# Create and enter the build directory
mkdir build && cd build

# Configure the project with CMake
cmake ..

# Build the executable
cmake --build .
Run the program:

bash
# On Linux/macOS
./TypingSpeedTest

# On Windows
TypingSpeedTest.exe
Usage Guide
Launch the application

Select a typing mode (Code, Standard, or Sprint) by clicking

Type the displayed text as accurately and quickly as possible

Finish either by pressing Enter or typing the full text

Review your results including speed, accuracy, total words, and time taken

Reset to retry or go back to mode selection as desired

Minimum System Requirements
Operating System: Windows 7 or later, macOS 10.12 or later, Linux kernel 3.x or later

Processor: x86_64 or equivalent

Memory: At least 1 GB RAM

Graphics: OpenGL 3.3 compatible GPU or equivalent software renderer

Input Devices: Keyboard and mouse
