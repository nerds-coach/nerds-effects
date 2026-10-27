<p align="center"><img src="icon.svg" width="128" height="128" alt="NERDS Effects icon"></p>

<h1 align="center">NERDS Effects</h1>

<p align="center"><b>Motion graphics and visual effects.</b> Part of the NerdsCraft Suite: install it with
<a href="https://github.com/nerds-coach/nerds-launcher/releases/latest">NERDS Launcher</a>.</p>

NERDS Effects is [EffectCraft](https://github.com/storytold/effectcraft), ArtCraft's free and open-source app, built
with the NERDS icon. This repository holds no app code: its [build workflow](.github/workflows/build.yml)
takes each official EffectCraft release, swaps in the NERDS icon (`app-icon/`, laid over the app's own
`assets/app-icon/`), builds it for Windows and macOS on GitHub, and publishes it under
[Releases](../../releases) with the same version and file names. It checks for a new release every
six hours.

The app's code and its license (MIT OR Apache-2.0) are EffectCraft's: see
[storytold/effectcraft](https://github.com/storytold/effectcraft). The NERDS icon is a NERDS brand asset.

To build now: **Actions → Build → Run workflow** (tick *force* to rebuild a version already here).
