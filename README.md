# RASTA Universal Audio IR Remote v9 FINAL

One Android app for:
- Onkyo CR-185 / RC-332S
- Sony CMT-E300HD / RM-E02D
- Victor/JVC NX-TC5-B / RM-SNXTC5-S

## Core
- Xiaomi Android IR transmitter via ConsumerIrManager
- Persistent IR Code Memory using SharedPreferences JSON
- Candidate / VERIFIED / FAILED records
- Export / Copy / Import database
- Code Lab with manual protocol parameters
- Safe discovery workflow: unverified values are never presented as verified

## Factory sound controls represented in UI
### Onkyo CR-185 / RC-332S
- TONE: BAS, TRE, BAL
- Bass/Treble: -10..+10
- Balance: L3..R3 / center 0
- S.BASS
- DIRECT
- MUTE and VOLUME

### Sony CMT-E300HD / RM-E02D
- M.BASS
- Preset EQ
- Volume / Mute
- Full documented transport/navigation controls

### Victor/JVC NX-TC5-B / RM-SNXTC5-S
- AHB PRO
- Sound Mode: Manual EQ, Live, Rock, Pop, Classic, Dance
- Manual EQ: Treble -5..+5, Bass -5..+5
- Volume / Mute
- Full documented remote control surface

## Important accuracy policy
Sony RM-E02D and JVC RM-SNXTC5-S model-specific command tables are not fabricated. Their UI controls are present and are routed to the Code Lab until an exact command is verified. Candidate values can be tested and saved; only confirmed codes should be marked VERIFIED.

## Build
Open in Android Studio and build the app module. The project uses the Android SDK/Gradle setup included in the project.
