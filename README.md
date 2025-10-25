Typing Speed Test
A professional-grade typing speed test application written in C using the raylib graphics library.

Features
Three test modes: Code, Standard, Sprint

Real-time input capture with instant feedback

WPM and accuracy calculation

Detailed results and suggestions

Cross-platform GUI (raylib)

Prerequisites
C compiler (GCC/Clang/MSVC, C11 support)

raylib library

CMake 3.10 or higher

Installing raylib
For Ubuntu/Debian:

bash
sudo apt install libraylib-dev
For Fedora:

bash
sudo dnf install raylib-devel
For macOS (Homebrew):

bash
brew install raylib
For Windows:
Use vcpkg or download binaries from the raylib website.

Build and Run
Clone the repository:

bash
git clone https://github.com/yourusername/TypingSpeedTest.git
cd TypingSpeedTest
Create and enter the build directory:

bash
mkdir build && cd build
Configure the project with CMake:

bash
cmake ..
Build the executable:

bash
cmake --build .
Run the program:

On Linux/macOS:

bash
./TypingSpeedTest
On Windows:

bash
TypingSpeedTest.exe
Usage
Start the application

Select one of the three modes

Type the provided text as accurately and quickly as possible

Press Enter or type the entire text to finish

View your results and feedback

Reset or return to menu as needed

Minimum System Requirements
OS: Windows 7/macOS 10.12/Linux kernel 3.x or higher

CPU: x86_64

Memory: 1 GB RAM minimum

Graphics: OpenGL 3.3 compatible

Input: Keyboard and mouse
