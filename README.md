# Pioneered-XZ

Pioneer XDJ-XZ-inspired Mixxx skin, Pioneer DDJ-FLX4 controller mapping, and touchscreen keyboard integration for Raspberry Pi, designed to run on top of [ghztomash/StandaloneMixxx](https://github.com/ghztomash/StandaloneMixxx).

## v1.0.0 — Initial Public Release

The tested Pioneered-XZ v1.0.0 installer is now available: [download the release ZIP](https://github.com/mikayla-fox/Pioneered-XZ/releases/tag/v1.0.0).

The package includes the touchscreen skin, DDJ-FLX4 mapping, 10 custom FX chain presets, SEARCH/X keyboard helper, patched fullscreen Wayland keyboard, and automated installer with configuration backups.

**Known issue:** The PITCH FX preset does not currently work properly due to a latency issue.

## Platform and compatibility

Tested on a Raspberry Pi 4B (4GB) with the custom Mixxx 2.7 build from [StandaloneMixxx](https://github.com/ghztomash/StandaloneMixxx), an 800×480 touchscreen, Wayland/labwc, and Pioneer DDJ-FLX4. Compatibility with other setups has not been verified. The touchscreen helper targets the `generic ft5x06` device; installations under usernames other than `mix` may need adaptation.

## Installation

1. Set up Mixxx using [ghztomash/StandaloneMixxx](https://github.com/ghztomash/StandaloneMixxx).
2. [Download Pioneered-XZ v1.0.0](https://github.com/mikayla-fox/Pioneered-XZ/releases/tag/v1.0.0) and extract the ZIP on the Raspberry Pi.
3. Close Mixxx, open a terminal in the extracted folder and run `bash install.sh`.
4. Select the Pioneered-XZ skin and DDJ-FLX4 controller mapping in Mixxx.
5. Reboot the Raspberry Pi.

**Important:** The installer backs up existing FX configurations and replaces user FX chain presets with the 10 Pioneered-XZ presets.

## Credits

Pioneered-XZ builds on these open-source projects:

- [timewasternl — Pioneered](https://github.com/timewasternl/Pioneered): original Pioneered Mixxx skin, forming the foundation of the touchscreen interface.
- [ghztomash — FLX-Mixxx](https://github.com/ghztomash/FLX-Mixxx): updated DDJ-FLX4 mapping forming the foundation of the controller integration.
- [ghztomash — StandaloneMixxx](https://github.com/ghztomash/StandaloneMixxx): Raspberry Pi standalone Mixxx environment that Pioneered-XZ is designed to complement.

Special thanks to these creators and the wider Mixxx community. The controller mapping also incorporates work credited in its source to Warker, nschloe, dj3730, jusko, Robert904, tomash_ghz and mikayla.fox.

Pioneered-XZ is an independently developed modification and extension of these projects.

## Development history

**v1.0.0** is the initial public release of the tested Pioneered-XZ installer and configuration.
