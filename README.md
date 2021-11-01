# adduser-dll
Simple DDL that add a user to the local Administrators group

## Build

Open the solution to Visual Studio (tested only on Visual Studio 2019 Community Edition) and compile the DLL in Release mode for your target architecture (x64, x86).

### Customize

To create custom user just edit the file `dllmain.cpp` with the desired username, password and group.

## Usage

* Standalone: `rundll32.exe .\adduser.dll,backDoor`
* Chain: use the DLL to be inject o called from another script/tool.
