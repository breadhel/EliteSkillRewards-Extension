# EliteSkillRewards-Extension

An EliteMobs addon that allows admins to reward player skill levels with commands while keeping EliteMobs' native progression system, animations, and effects.

## Overview

EliteSkillRewards-Extension adds a simple administration tool for EliteMobs servers, allowing staff members to manually grant skill levels to players while still using EliteMobs' own skill progression system.

Skill rewards are applied through EliteMobs' internal XP system, meaning players receive the same level-up experience as normal gameplay, including EliteMobs' original animations, sounds, particles, and displays.

## Features

- Grant EliteMobs skill levels using a simple command
- Uses EliteMobs' native skill progression system
- Keeps official EliteMobs level-up animations, sounds, and effects
- Built-in command tab completion
- Supports all EliteMobs skills
- Lightweight and easy to use

## Requirements

- Minecraft 1.21.x
- Paper server
- EliteMobs installed

## Installation

1. Download the latest EliteSkillRewards-Extension `.jar`
2. Place the `.jar` file into your server's `plugins` folder
3. Ensure EliteMobs is installed and running
4. Restart your server
5. Use `/emskill` to begin rewarding skills

## Commands

### `/emskill add <player> <skill> <amount>`

Adds the specified amount of levels to a player's EliteMobs skill.

Example:

/emskill add Steve SWORDS 5

This will give Steve 5 additional SWORDS skill levels.

## Permissions

### `elitemobs.skill.admin`

Required permission to use the `/emskill` command.

## Skill Types

The skill argument uses EliteMobs' skill names.

Examples:

SWORDS  
AXES  
BOWS  
ARMOR

You can use tab completion in-game to view all available skills.

## Usage Example

A server administrator wants to reward a player for completing an event:

/emskill add PlayerName ARMOR 3

The player receives 3 ARMOR skill levels, and EliteMobs handles the normal skill progression effects, animations, sounds, and displays.

## Notes

EliteSkillRewards-Extension uses EliteMobs' internal skill system to provide a seamless experience. Because it relies on EliteMobs internals, future EliteMobs updates may require compatibility updates.

## License

MIT License
