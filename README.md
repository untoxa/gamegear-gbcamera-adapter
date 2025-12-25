# Game Boy cartridge to Game Gear adapter

This adapter was designed to be used with reflashable Game Boy Cameras running the Game Gear version of the "Photo!" ROM,
which is a custom Game Boy Camera ROM. It can be downloaded here: https://github.com/untoxa/gb-photo/releases/latest/

In addition to "Photo!" this adapter can be used to run your own Game Gear homebrew ROMs on reflashable Game Boy carts. However this adapter will not allow playing Game Boy games on the Game Gear without rewriting them.

TODO: add details

## Schematic

![Showcase](doc/Images/schematics.jpg)

## Bill of materials (BOM)

### Chips:

| ID       | Soviet  | Name     |
| -------- | ------- | -------- |
| DD1      | К555ТМ2 | SN74LS74 |
| DD2      | К555ЛП5 | SN74LS86 |
| DD3, DD5 | К555ЛН1 | SN74LS04 |
| DD4      | К555ЛЛ1 | SN74LS32 |

### Other:

- One 10 KOhm resistor
- Three 104 ceramic capacitors
- One Game Boy Cart connector
- One PLD 2,54mm two row male connector
- One PLD 2,54mm two row female connector
- The standard Game Gear cart shell

## Photo! running on the Game Gear using the GameBoy-to-GameGear adapter:
![Showcase](doc/Images/Showcase_GameGear.jpg)
