# dnd-hugo

This is a hugo theme for documenting dungeons and dragons (DnD) campaigns.

It is still a work in progress.

## Features

- Automatic Campaign Pages
    - extentable with custom content in respective `_index.md`
    - automatic list of PCs
    - automatic list of NPCs
    - automatic list of sessions
- Session pages for detailed session recaps
    - campaign
    - date
- Character pages
    - characterType (pc / npc)
    - class
    - race
    - campaign
- Spell pages

## Installation

1. Add the theme
  ```
  git add submodule https://github.com/sekthor/dnd-hugo.git themes/dnd-hugo
  ```
2. use the theme by using

## Configuration

## Usage

- Create a Campagin
  ```
  hugo new content campaings/<campaign-name>/_index.md
  ```
- Create a character
  ```
  hugo new content characters/<character-name>/index.md
  ```
- Create a spell
  ```
  hugo new content spells/<spell-name>.md
  ```

# Acknowledgements

## Fonts

- Dwarvish: [Davek](https://www.dafont.com/davek.font)
- Elvish: [Rellanic](https://www.dafont.com/rellanic.font)
- Draconic: [Iokharic](https://www.dafont.com/iokharic.font)
- Abyssal: [Barazhad](https://www.dafont.com/barazhad.font)
