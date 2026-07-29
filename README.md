# EliteSkillRewards-Extension

EliteSkillRewards-Extension is an EliteMobs addon that allows server administrators to reward players with EliteMobs skill levels and XP through simple commands.

The addon integrates directly with EliteMobs' skill system, allowing rewards to work with EliteMobs' normal progression instead of creating a separate leveling system.

Players keep EliteMobs' native XP handling, skill calculations, progression, displays, sounds, particles, and level-up effects.

## Features

- Reward players with EliteMobs skill levels
- Reward players with custom amounts of EliteMobs skill XP
- Uses EliteMobs' native skill progression system
- Supports all EliteMobs skills
- Keeps EliteMobs progression behaviour
- Command tab completion support
- Lightweight and easy to use
- Designed for events, giveaways, rewards, competitions, and server management

## Requirements

- Minecraft: 1.26.1
- Paper server
- EliteMobs 11.x
- Java 25+

May work on Minecraft 1.21.8+ versions, but compatibility depends on EliteMobs updates.

## Installation

1. Download the latest EliteSkillRewards-Extension.jar
2. Place the jar file into your server's plugins folder
3. Make sure EliteMobs is installed and working correctly
4. Restart your server
5. Use the commands below

## Commands

### Add Skill Levels

Command:

/emskill add <player> <skill> <levels>

Example:

/emskill add Steve SWORDS 5

This gives Steve 5 additional SWORDS skill levels using EliteMobs' normal progression system.

---

### Add Skill XP

Command:

/emskill xp <player> <skill> <amount>

Example:

/emskill xp Steve SWORDS 10000

This gives Steve 10,000 SWORDS XP while allowing EliteMobs to handle progression normally.

## Permissions

Permission:

elitemobs.skill.admin

Required permission to use EliteSkillRewards commands.

## Supported Skills

EliteSkillRewards uses EliteMobs' built-in skill system.

Examples:

SWORDS
AXES
BOWS
ARMOR

All available EliteMobs skills can be selected using command tab completion.

## Version History

## EliteSkillRewards-1.0.5

Bug Fixes & Improvements:

- Fixed skill XP rewards not properly triggering level-up notifications
- Improved EliteMobs skill progression handling
- Fixed XP and level calculation issues
- Improved command reliability
- General stability improvements

## EliteSkillRewards-1.0.0

Initial Release:

- Added skill level rewards
- Added skill XP rewards
- Added EliteMobs skill integration
- Added command tab completion

## How It Works

EliteSkillRewards-Extension does not replace EliteMobs' skill system.

Instead, it communicates with EliteMobs directly so that:

- XP remains stored by EliteMobs
- Levels are calculated by EliteMobs
- Players keep normal EliteMobs progression
- Rewards feel like normal EliteMobs progression

## Compatibility Notes

EliteSkillRewards uses EliteMobs internal skill classes for deeper integration with the EliteMobs progression system.

Because of this, major EliteMobs updates may require compatibility updates if internal systems change.

## Support

If you find a bug, have a suggestion, or need help, create an issue on GitHub.

## License

MIT License
