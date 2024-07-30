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
    or using ssh
    ```
    git add submodule git@github.com:sekthor/dnd-hugo.git themes/dnd-hugo
    ```
2. use the theme by using

## Configuration

## Usage

### Create a Campagin

```
hugo new content campaings/<campaign-name>/_index.md
```

### Create a character

```
hugo new content characters/<character-name>/index.md
```

In the frontmatter, speficy the `class` and `race`.
In the characterType, spefcify, if this character is played by a player (`pc`) or is a `npc`.

If you would like to add a picture for your character, place a `profile.png` file in the `characters/<character-name>` folder.

### Create a spell

```
hugo new content spells/<spell-name>.md
```

Fill in the front matter to specify

- castingtime
- range
- components
- duration