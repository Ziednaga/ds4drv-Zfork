# ds4drv-Zfork
ds4drv zFork is a Sony DualShock 4 userspace driver for Linux based on the original chrippa/ds4drv to run in the modern Python 3.13.2+ with Bluez Bluetooth.

See original chrippa/ds4drv git: https://github.com/chrippa/ds4drv

Features

    Option to emulate the Xbox 360 controller for compatibility with Steam games
    Setting the LED color
    Reminding you about low battery by flashing the LED
    Using the trackpad as a mouse
    Custom mappings, map buttons and sticks to whatever mouse, key or joystick action you want
    Settings profiles that can be cycled through with a button binding

Installing
Dependencies

    Python 3.13.2+ (https://www.python.org/downloads/)
    hcitool (usually available in the bluez-utils or bluez-deprecated)

These packages will normally be installed automatically by the setup script, but you may want to use your distro's packages if available:

    pyudev 0.16 or higher
    python-evdev 0.3.0 or higher

