# Crystals by AEM

A phone lightsaber you ignite by swiping up. Pick a crystal, light it, swing your phone, clash, block and drag the blade, with real sound fonts and haptics that follow every move.

<p align="center">
  <img src="screenshots/1.png" width="200">
  <img src="screenshots/2.png" width="200">
  <img src="screenshots/3.png" width="200">
  <img src="screenshots/4.png" width="200">
</p>

## What it does

- **15 crystals**, each a 3D gem with its own colour, sound and blade look.
- **Full-screen blade**: a white core with a glowing edge in the crystal's colour, growing up the screen.
- **Real sound fonts**: hum, swings, clashes, blasts, locks, drags, power-on and retraction sounds.
- **Motion controls**: swing, clash, stab and drag by moving your phone.
- **Haptics**: a constant hum while lit that grows with your swings, and a heavy hit on clashes (best on Android).
- **Unique looks per font**: each font follows its own ignite and retract timing, flicker, swing flare and colours.

## Controls

| Do this | Get this |
|---|---|
| Swipe up | Ignite |
| Swipe down | Retract |
| Swipe sideways on the crystal | Spin it |
| Arrows / name pill | Switch crystal |
| Swing the phone | Swing sound and flare |
| Hit something or snap the phone | Clash |
| Thrust forward | Stab |
| Tap the lit screen | Block a blast |
| Hold the lit screen | Saber lock |
| Tilt the top of the phone down | Drag the blade tip |
| Hold the crystal | Long power-on (fonts with a preon sound) |
| Gear icon | Settings |

## Crystals

Crimson and Senate Majority, then the Greyscale fonts: Analog, Crispity, Magnetic, Mercenary, Masterless, Noble, Deadlink, Seethe, Grey, Volatile, Ra, Apocalypse and Exalted.

## Easter egg

Swipe down on a resting crystal to break it. Put the pieces back together and it comes back unstable and cracked. Hold the name to restore it.

## Install (Android)

1. Open the **Releases** page and download the latest `.apk`.
2. Open it on your phone and allow installs from your browser or file manager if asked.
3. Launch **Crystals**.

The package name is `crystals.aem`. Built automatically with GitHub Actions.

## Build it yourself

The whole app is one file, `lightsaber.html`, wrapped in an Android WebView by `.github/workflows/build.yml`. Push to GitHub and run the workflow to get an APK.

## Credits

Sound fonts by **Greyscale Fonts** (Analog, Crispity, Magnetic, Mercenary, Masterless, Noble, Deadlink, Seethe, Grey, Volatile, Ra, Apocalypse, Exalted, https://www.greyscalefonts.com/) 
and the Senate Majority Proffieboard font. Blade looks are based on each font's Proffieboard blade style. All sound fonts belong to their authors.
