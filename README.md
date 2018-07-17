# App2deb
Automatically create deb files out of tvOS or iOS ipas that can be run from /Applications.

## Info
The Installer script will automatically check for all dependancies and install them if needed using the package manager you currently have installed (Homebrew or MacPorts). If you do not have a package manager installed, it will install Homebrew and then the dependancies.

## Usage
1. Download and run the "Install" executable. (cd to the directory with Install and run ./Install in terminal)
2. Move to the directory that holds your IPA
3. Run App2deb [IPA]
