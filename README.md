# Convergence Bard Bot Command Guide

### Start Script
- Command: `/lua run convbard`
- Description: Starts the Lua script Convergence Bard.

## General Bot Commands
These commands control general bot functionality, allowing you to start, stop, or save configurations.

### Toggle Bot On/Off
- Command: `/convbard Bot on/off`
- Description: Enables or disables the bot for automated functions.

### Save Settings
- Command: `/convbard Save`
- Description: Saves the current settings, preserving any configuration changes.

---

### Set Assist Parameters
- Command: `/convbard Assist <name> <range> <percent>`
- Description: Sets the main assist name, assist range, and assist health percentage.

---

## Camp and Navigation
These commands control camping behavior and movement options.

### Set Camp Location
- Command: `/convbard CampHere`
- Description: Sets the current location as the designated camp location.

### Set Camp Distance
- Command: `/convbard CampDistance <distance>`
- Description: Defines the maximum distance from the camp location.
- Usage: `/convbard CampDistance 100` sets a 100-unit radius.

### Return to Camp
- Command: `/convbard Return on/off`
- Description: Enables or disables automatic return to camp if moving too far.

### Toggle Chase Mode
- Command: `/convbard Chase <target> <distance>` or `/convbard Chase on/off`
- Description: Sets a target and distance for the bot to chase, or toggles chase mode.
- Example: `/convbard Chase John 30` will set the character John as the chase target at a distance of 30.
- Example: `/convbard Chase off` will turn chasing off.

---

## Combat and Assist Commands
These commands control combat behaviors, including melee assistance and target positioning.

### Set Assist Melee
- Command: `/convbard AssistMelee on/off`
- Description: Enables or disables melee assistance.

### Toggle Stick Position (Front)
- Command: `/convbard StickFront on/off`
- Description: Sets the bot to stick to the front of the target.

### Toggle Stick Position (Back)
- Command: `/convbard StickBack on/off`
- Description: Sets the bot to stick to the back of the target.

### Stick Distance
- Command: `/convbard StickDistance <distance>`
- Description: Sets the distance to stick to a target.

---

## Pulling and Mob Control
These commands manage mob pulling, setting levels, distances, and mob retention in the camp area.

### Pull Amount
- Command: `/convbard PullAmount <amount>`
- Description: Defines the number of mobs to pull.

### Pull Distance
- Command: `/convbard PullDistance <distance>`
- Description: Sets the maximum distance to pull mobs.

### Pull Level Min/Max
- Command: `/convbard PullLevelMin <level>` and `/convbard PullLevelMax <level>`
- Description: Specifies the minimum and maximum levels of mobs to pull.

### Pull Pause Timer
- Command: `/convbard PullPauseTimer <timer>`
- Description: Sets the pull pause timer duration.

### Keep Mobs In Camp Amount
- Command: `/convbard KeepMobsInCampAmount <amount>`
- Description: Sets the number of mobs allowed within the camp radius.

### Toggle Keep Mobs In Camp
- Command: `/convbard KeepMobsInCamp on/off`
- Description: Enables or disables keeping mobs within the camp area.

---

## Song Management
Commands to manage song twisting and individual song settings.

### Toggle Sing Songs
- Command: `/convbard SingSongs on/off`
- Description: Enables or disables automatic song twisting.

### Sing Specific Song
- Command: `/convbard SingSong <songtype> on/off`
- Description: Enables or disables a specific song.
- Valid song options include: `run`, `magic`, `fire`, `cold`, `disease`, `poison`, `mez`, `slow`, `aggro`

---

## Mesmerize Control
Commands to manage the mesmerize functionality.

### Set Mesmerize Radius
- Command: `/convbard MesmerizeRadius <radius>`
- Description: Sets the radius for mesmerize effects.

### Set Mesmerize Stop Percent
- Command: `/convbard MezStopPct <percent>`
- Description: Sets the health percentage to stop mesmerizing.

---

## Additional Commands

### Toggle Pulling
- Command: `/convbard Pull on/off`
- Description: Enables or disables pulling behavior.

### Pull Pause
- Command: `/convbard PullPause on/off`
- Description: Pauses or resumes pulling.