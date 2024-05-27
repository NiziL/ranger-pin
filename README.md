# ranger-pin

Simple plugin to add a pin feature to ranger, based on the scaffold plugin by [hut](https://github.com/hut).

This plugin defines:
- two commands to pin and unpin items
- a new sorting function named `pin`, based on `pathname_natural_lower` (aka natural, case insensitive)
- a new colorscheme context named `pin`
- a new `pinned` file in `~/.config/ranger` to save the pinned path

## Installation

1. Copy `plugins/pin.py` into `.config/ranger/plugins`
2. Copy `colorschemes/pin.py` into `.config/ranger/colorschemes`  
   **alternative:** create your own colorscheme to handle the new `pin` context
3. Update `.config/ranger/rc.conf`
    - **mandatory:** modify the sort function: `set sort pin`
    - **optional:** modify the colorscheme to ensure the pinned items are colorized
      `set colorscheme pin` if you're using the provided colorscheme

## Usage

- `++` shortcut to pin
- `--` shortcut to unpin
