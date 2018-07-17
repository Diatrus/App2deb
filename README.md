# App2deb
App2deb is a simple, minimal footprint script that will extract an IPA and repack it into a deb made for installing on an Apple TV or iOS device respectively.

## How does it work?
App2deb extracts an IPA, takes needed info from the info.plist to create a specialized control file, adds entitlements to the main binary and frameworks (so the app can be ran as root), then repacks it into a deb that will install the app to /Applications.

## Instructions
1. Download the latest Installer from the releases page.
2. Simply double click the Installer, type your password when prompted, and let the script install App2deb and its dependencies.
3. Run App2deb [/path/to/ipa] to repack your IPA.
4. Fill in the author (creator of app) and maintainer (most likely you) information when prompted.
5. The output file will be displayed after the command completes successfully.

## Installer Info
The Installer script will automatically check for all dependancies and install them if needed using the package manager you currently have installed (Homebrew or MacPorts). If you do not have a package manager installed, it will install Homebrew and then the dependancies.

## Updating
Simply rerun the Installer script. It automatically pulls the latest App2deb from Github and installs it
