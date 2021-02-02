<div align = center><h1>📡 Updates</h1></div>
<div align = center><p>A feed where updates for my programs are linked.<br>Please note that Gists updates are not uploaded here.</p></div>
<br/>
<br/>

## [BackToMac v1.2.0](https://github.com/datcuandrei/BackToMac/releases/tag/v1.2.0)
### Feb 02, 2021
- Added the ability to choose custom OS images : Users can now create USB sticks with their own image files.Currently,BackToMac supports only `.iso` and `.cdr` image files.(thanks to @Minh-Ton for the idea.)
- Added in-app aspect switcher : Users can now switch between light mode and dark mode from within the app,without the need to relaunch the app with different executable.
- Added a setup : BackToMac will now come with an installer and uninstaller.See *README.md* to find out how to install and use BackToMac.
- Switched to `pkexec` : BackToMac used to launch with root privileges with the help of `sudo su` in the launch script.In order to make BackToMac a fully GUI-based tool,it now uses `pkexec`,which is the graphical way to gain root privileges.

## [i3wm-xfkeys v1.0](https://github.com/datcuandrei/i3wm-xfkeys/releases/tag/v1.0)
### Jan 22, 2021
- Changed name from `i3wm-mac-syskeys` to `i3wm-xfkeys`.
- Works with any machine(hence the name change).
- Brightness will now work with all machines (reference to issue #1 ).
- Same goes with keyboard backlights.
- Added support for media controls (requires `playerctl`).
- Improved code.

## [dafetch v1.0](https://github.com/datcuandrei/dafetch/releases/tag/v1.0)
### Jan 6, 2021
- Changed name from yfetch to dafetch.
- Added support for Puppy Linux and Peppermint OS.
- Fixed Manjaro ASCII Art.
- Removed Machine ID in favor of DE/WM.
- Removed all code referencing CPU info,as dafetch only retrieves OS info.
- Uptime can also show days now.

## [dafetch v0.2](https://github.com/datcuandrei/dafetch/releases/tag/v0.2)
### Jan 6, 2021
- Fixed an issue where Pop!_OS wouldn't be recognized(misspelled the name,oops).
- Added ASCII art for Void Linux.
- Fixed the colors for Fedora and Solus.

## [dafetch v0.1](https://github.com/datcuandrei/dafetch/releases/tag/v0.1)
### Jan 5, 2021
Preview:"Supported distros

- Arch(btw)
- Debian
- Fedora
..."

## [BackToMac v1.1.0](https://github.com/datcuandrei/BackToMac/releases/tag/v1.1.0)
### Dec 30, 2020
- Added patchers from [RMC Team](https://rmc-team.github.io/) : from now on,after hitting `Proceed`,the user is greeted with an option to choose between the patcher from RMC and dosdude1.This feature will not affect users that have a supported Mac,since no patches will be applied to their systems.
- Fixed UI elements.
- Made UI more responsive.
- Updated launch script.

## [MacLinuxUtils v2.3.1](https://github.com/datcuandrei/MacLinuxUtils/releases/tag/v2.3.1)
### Dec 28, 2020
- Fixed an issue where,on Macs that do not use Turbo Boost,it wouldn't boot.
- Fixed an issue where,on experimental mode,presets that didn't have a manual config saved wouldn't work.
- Added info related to system tray icon support on different DE's in README.

## [MacLinuxUtils v2.3.0](https://github.com/datcuandrei/MacLinuxUtils/releases/tag/v2.3.0)
### Dec 11, 2020
Preview:"Manual mode (Experimental)
Manual mode is a more advanced automatic mode.It let's you set..."

## [BackToMac v1.0.2](https://github.com/datcuandrei/BackToMac/releases/tag/v1.0.2)
### Nov 24, 2020
- Fixed an issue where BackToMac would not download operating systems.

## [BackToMac v1.0.1](https://github.com/datcuandrei/BackToMac/releases/tag/v1.0.1)
### Nov 6, 2020
- Updated Instructions :
   1. Informed users regarding BackToMac on VMs not working as expected;
   2. Formatting the USB now better explained;
 - Fixed UI elements.
 - After running the launch script,the terminal is usable;the terminal doesn't wait for the user to exit the program.
 -Author page now redirects to my website instead of my GitHub profile.


## [MacLinuxUtils v2.0](https://github.com/datcuandrei/MacLinuxUtils/releases/tag/v2.0)
### Oct 8, 2020
Preview:" - Backend improved!
The backend of the program was drastically changed : The code is now split into different classes,each serving differe..."

## [BackToMac v1.0](https://github.com/datcuandrei/BackToMac/releases/tag/v1.0)
### Oct 4, 2020
Preview:"An automated utility for Linux that creates bootable macOS USB sticks.    For more information on how to get started and..."


## [Minotes v1.0](https://github.com/datcuandrei/Minotes/releases/tag/v1.0)
### Sep 26, 2020
- The UI is now more responsive.
- Minotes will now use the OS's look and feel.
- Added an option to delete notes.
- Created a special folder where the notes will be stored(the location can still be modified with ease).
- Replaced the "File" button with "Notes" button.

## [MacLinuxUtils v1.1.1](https://github.com/datcuandrei/MacLinuxUtils/releases/tag/v1.1.1)
### Sep 8, 2020
- Added OS identification (Windows , OSX) when checking if it is a Mac or not running Linux.
- Added "Attribution" button.
- Fixed an issue where the error for non-Apple hardware was not displaying correctly.

## [MacLinuxUtils v1.01](https://github.com/datcuandrei/MacLinuxUtils/releases/tag/v1.01)
### Sep 7, 2020
- Fixed an issue where the program would still run on non-Apple hardware or non-Intel based Mac.

## [MacLinuxUtils v1.0](https://github.com/datcuandrei/MacLinuxUtils/releases/tag/v1.0)
### Sep 7, 2020
Preview:"On macOS,there are tools for controlling the fan speeds,switching turbo boost on or off,etc.Sadly,Mac users on Linux have no alternatives for such tools.
MacLinuxUtils's aim is to bring..."

## [Minotes b0.8.5](https://github.com/datcuandrei/Minotes/releases/tag/b0.8.5)
### Jun 21, 2020
- Fonts will be found automatically by the program.
- Renamed "Bullets & Lists" to "Punctuating lists".
- Readded "Format" Label in front of the formatting.
