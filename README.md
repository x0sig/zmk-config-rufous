# Rufous ZMK Firmware

Firmware and personal keymap for [rufous](https://github.com/jcmkk3/trochilidae/tree/main), a ergo wireless keyboard.

![keymap image](img/rufous.svg)

## Building

Generate the firmware via the GitHub action.
To build locally check [zmk docs](https://zmk.dev/docs/development/setup).

This will produce the file `zmk/app/build/zephyr/zmk.utf`. Put the board into
bootloader mode by pressing the reset button twice, and copy this file to the
board, which will show up as a USB drive when connected to your computer. Repeat
for the right side board.

## Config

Use [zmk-helpers](https://github.com/urob/zmk-helpers), check respective docs and zmk official docs.
Small changes can be rather straight forward by editing `config/puffer.keymap`.

## Keymap image

The keymap image is created using [keymap-drawer](https://github.com/caksoylar/keymap-drawer).
It can be regenerated with the commands:

## Resources

- https://github.com/urob/zmk-helpers
- https://github.com/urob/zmk-config
- https://github.com/caksoylar/keymap-drawer
