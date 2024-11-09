# Changelog and progress update
This is here for changelog and progress update (no way!?!?!). Mostly for tracking what I need to get done and stuff, but you can use it to see if I'm slacking (I probably am).

## Changelog

- **Changelog 1.21**: Fixed bugs (Discord stop changing class names) with body of profile, adjusted for Discord updates
- **Changelog 1.20**: Fixed roles overlapping with note button, profiles look kinda weird still because extra margin on descriptionClamp
- **Changelog 1.20 Beta**: Finally got around to fixing the note button, a few pixels offset but good enough
- **Changelog 1.16**: Finally added support for new Discord release, notes are still broken as of now (they appear but always on the "Message user" textbox). 
- **Changelog 1.15**: Added "VIEW PROFILE" text, added a notes section, still a bug because Notes section is measured relative to top rather than relative to desc. clamp, will fix (if possible) in 1.2 
- **Changelog 1.1**: Added support for custom status messages, added line break between name/status and desc. clamp
- **Changelog 1.0**: Added "ABOUT ME" text, allowed for up to 19 lines of desc. clamp, allowed support for badges and made them better (3px padding + 10px border-radius)
- **Changelog 0.5**: Allowed for up to 7 lines of desc. clamp, added centre thing to resemble 2023 profiles (BG of body is no longer solid colour), added and removed linebreak (no padding at bottom)
- **Changelog 0.1**: Planning, used OldCord CSS and old profile pictures from web to see what was needed, created CSS File

## Progress and other

- 9 September 2024: New Discord (major?) update: rewrite of classes 😢
- 29 October 2024: Started making this css

## Screenshots

![alt text](https://github.com/thatpanda0/BetterDiscord/blob/main/Images/preview.png)
![alt text](https://github.com/thatpanda0/BetterDiscord/blob/main/Images/Untitled.png)

If you couldn't tell what changed:
- Added "+Add Status" button at top
- Newline below Add status button
- Status messages now show inside the profile not in a bubble (yipee)
- Description can be longer than 3 lines (up to 190 lines)
- Added note section (moved button to bottom)
- Added labels
- Added "View Profile" text on PFP hover
- Added inner box thing to resemble 2023's theme
- Badges have more padding and border radius
