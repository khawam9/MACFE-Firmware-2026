# HelloWorld — MACFE-Firmware-2026

A simple C++ "Hello World" program.

## Prerequisites

-**Compiler:** g++ (MinGW), tested with the MinGW toolchain at C:\MinGW\bin\g++.exe
- **OS:** Windows (adjust paths for Linux/Mac if needed)

## Project Structure

HelloWorld/
├── HelloWorld.cpp     # source file
├── output/             # compiled binaries go here
└── README.md

## Build

From the project root, compile with:

'''bash
g++ -Wall -Wextra -g3 HelloWorld.cpp -o output/HelloWorld.exe 
'''

Flags:

- '-Wall -Wextra' — enable extra compiler warnings
- '-g3' — include full debug symbols (useful for gdb/VS Code debugging)

## Run

'''bash
output\HelloWorld.exe
'''

(On Linux/Mac: ./output/HelloWorld.exe)

## Notes
Make sure the source file has a '.cpp' extension — g++ won't recognize it as source code otherwise.
If 'g++' isn't found, confirm MinGW's bin folder is on your system 'PATH', or call it via its full path as shown above.