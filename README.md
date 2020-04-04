# Chad's Dynamic Menu (dmenu)

This is my own build of the effecient dynamic menu for X.

## Patches included in this build

- center
- highlight
- lineheight
- numbers

## Requirements

In order to build dmenu you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install

## Running dmenu

See the man page for details.
