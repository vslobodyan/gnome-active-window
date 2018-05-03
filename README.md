# gnome-active-window
Actions with the active Gnome 3 (Shell) window. Compatible with Wayland. A working replacement for some functions in wmctrl and xdotool.


### Quick steps

1. Install

2. Replace your wmctrl or xdotool commands with this script

3. Enjoy your favorite manipulations with active window under Wayland and Gnome Shell. :)

### Usage

`gnome-active-window COMMAND`

Where COMMAND can be one of the following options:

| command | description |
| --- | --- |
|`min` | Minimize the active window. |
|`close` | Gently close the active window. |
| | |
| `install` | Сreate a symbolic link to this script at `/usr/local/bin`. After that, you can run a script with a short name `gnome-active-window` from any path. |
| `uninstall` | Removing a symbolic link to this script from `/usr/local/bin` |

### Tips

You can use this script in the [run-or-raise](https://github.com/CZ-NIC/run-or-raise) extension for Gnome Shell or in the [gnome-magic-window](https://github.com/adrienverge/gnome-magic-window) script executed from the command line. Both work well under Wayland and Gnome Shell, allowing you to run programs or activate their already running windows on the desktop.


### TODO

* Get info about active window

* Undecorate / decorate win

* Send fake keyboard input
