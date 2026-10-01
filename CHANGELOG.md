# Akkato changelog

Version numbers: the game, the web service worker cache and the Android versionName all use the same number
(set in package.json of akkato-app, APP_VERSION in the game file, VERSION in play/sw.js). Android versionCode is the
workflow run number. 1.0.0 is reserved for the first store release.

## 0.7.2
- Speaker button in the button bar mutes or unmutes music and sound effects in one tap (remembered).

## 0.7.1
- Background music was far too quiet (about 5 times too low, with a drone below what phone speakers play). Louder and higher.

## 0.7.0
- 60 levels in six worlds (Meadow, Shoreline, Grove, Canyon, Frostfield, Night Garden) with a world card, a world-complete moment and a finale. Late-level difficulty tuned with bot runs.
- Daily challenge: same starting board each day, streak that forgives one missed day, +1 bonus star.
- Stars unlock backgrounds (Meadow 12, Shoreline 30, Dusk 55, Blossom 85).
- Sound: soft generative background music with volume control, softer pops, bell chime on wins, blast thump.
- Vibration on pops and blasts (Android app uses @capacitor/haptics; web uses the browser vibrate call where supported). Setting to turn it off.
- Win animation: confetti and stars that pop in.
- Settings: About and credits (AI-assistance line, privacy link, contact), Erase all progress.
- Logo on the web version links to the home page.

## 0.6.0
- Removed Dissolve and the Timed sprint mode.
- Helpers now arrive one at a time in Levels: Swap (level 3), Rewind (5), combo meter and Paint (7), frozen blocks (10), Color Clear (12). Each is explained when it arrives. Endless has them all.

## 0.5.0
- New: Rewind, Color Clear, ice tiles (from level 10), Endless challenge toggle.
- Level 8 eased (5-color collect goals about 30% smaller).
- Bomb blasts reach 2 blocks out (5x5, 7x7 from the third bomb in a chain); screen shake and flash.
- Version shown in Settings.

## 0.4.0 and earlier
- Prototype builds: Levels, Endless, Timed, Swap/Dissolve/Paint, idle hint, flatter early-level scoring (more moves, fewer points).
