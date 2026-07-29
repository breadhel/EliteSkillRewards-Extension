# EliteSkillRewards-Extension

An EliteMobs addon that allows server administrators to reward players with skill levels and XP through simple commands while keeping EliteMobs' native progression system, animations, sounds, particles, and effects.

## Overview

EliteSkillRewards-Extension is designed to give server staff more control over EliteMobs skill progression.

Whether you are rewarding players for events, achievements, competitions, giveaways, or special milestones, this addon provides an easy way to grant skill XP or levels without requiring manual grinding.

Unlike simple level editors, EliteSkillRewards uses EliteMobs' own internal skill system, meaning rewards are handled like normal EliteMobs progression.

Players still receive EliteMobs' skill updates, XP displays, level progression, level-up animations, sounds, particles, and effects.

## Features

* Give players EliteMobs skill levels
* Give players custom amounts of EliteMobs skill XP
* Uses EliteMobs' native skill progression system
* Keeps EliteMobs' level-up displays, sounds, particles, and effects
* Supports all EliteMobs skills
* Command tab completion support
* Lightweight and easy to use
* Designed for events, rewards, giveaways, and server management

## Compatibility

Made for:

* Minecraft 1.26.1
* Paper servers
* EliteMobs 11.x

May also work on Minecraft 1.21.8+ versions, but compatibility is not guaranteed due to EliteMobs internal changes.

## Requirements

* Paper server
* EliteMobs installed
* Java 25+

## Installation

1. Download the latest `EliteSkillRewards-Extension.jar`
2. Place the jar file into your server's `plugins` folder
3. Make sure EliteMobs is installed and working correctly
4. Restart your server
5. Use the commands below to begin rewarding players

## Commands

### Give Skill Levels

```
/emskill add <player> <skill> <levels>
```

Example:

```
/emskill add Steve SWORDS 5
```

This will give Steve 5 additional SWORDS skill levels while using EliteMobs' normal progression system.

### Give Skill XP

```
/emskill xp <player> <skill> <amount>
```

Example:

```
/emskill xp Steve SWORDS 10000
```

This will give Steve 10,000 SWORDS skill XP while allowing EliteMobs to handle XP progression, level calculation, and skill updates normally.

## Permissions

### `elitemobs.skill.admin`

Required permission to use EliteSkillRewards commands.

## Supported Skills

EliteSkillRewards uses EliteMobs' built-in skill system.

Examples:

```
SWORDS
AXES
BOWS
ARMOR
```

All available EliteMobs skills can be selected using the command tab completion system.

## Usage Examples

### Event Rewards

Reward a player after winning an event:

```
/emskill add PlayerName SWORDS 3
```

The player receives 3 SWORDS levels through EliteMobs' normal skill progression system.

### Custom XP Rewards

Reward a player for completing a challenge:

```
/emskill xp PlayerName ARMOR 5000
```

The player receives ARMOR XP while keeping EliteMobs' normal progression behaviour.

## How It Works

EliteSkillRewards-Extension does not create its own leveling system.

Instead, it connects directly with EliteMobs' existing skill system.

This means:

* XP is stored by EliteMobs
* Skill levels are calculated by EliteMobs
* EliteMobs skill displays continue working
* Player progression remains compatible with EliteMobs

## Compatibility Notes

EliteSkillRewards-Extension uses EliteMobs' internal skill classes to provide the closest possible integration with the original EliteMobs progression system.

Because this addon uses EliteMobs internal classes, major EliteMobs updates may require compatibility updates if internal systems or class names change.

## Support

If you encounter bugs, compatibility issues, or have suggestions, please create an issue on GitHub.

## License

MIT License
