# dnd-hugo

This is a hugo theme for documenting dungeons and dragons (DnD) campaigns.

It is still a work in progress.

## Features

- Content types
  - **Campaign Pages** with automatically generated list of appearing characters and NPCs and a list of the campaigns sessions.
  - **Session pages** for detailed session recaps.
  - **Character pages** for character descriptions as well as race, class, aligments, ...
  - **Spell pages** describing spells the characters can use.
- Fonts for languages (dwarfish, elvish, draconic, abyssal)

## Installation

1. Add the theme
  ```
  git add submodule https://github.com/sekthor/dnd-hugo.git themes/dnd-hugo
  ```

2. Use the theme
  ```toml
  theme = "dnd-hugo"
  ```

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
