# ranger-pin

Simple plugin to add a pin feature to ranger, based on the scaffold plugin by [hut](https://github.com/hut).

## Installation

1. Copy `plugins/pin.py` into `.config/ranger/plugins`
2. Copy `colorschemes/pin.py` into `.config/ranger/colorschemes`
3. Update `.config/ranger/rc.conf`
    - modify the colorscheme to ensure the pinned files and folders are colorized: `set colorscheme pin`
    - modify the sort function to pin: `set sort pin`

## Usage

- `++` shortcut to pin
- `--` shortcut to unpin
