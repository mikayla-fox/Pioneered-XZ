# Pioneered-XZ

Pioneer XDJ-XZ-inspired Mixxx skin, Pioneer DDJ-FLX4 controller mapping, and touchscreen keyboard integration for Raspberry Pi, designed to run on top of [ghztomash/StandaloneMixxx](https://github.com/ghztomash/StandaloneMixxx).

## v1.0 — packaging in progress

The first public release is being prepared from the previously tested **v136 overlay-keyboard** configuration. **The complete installer and release assets have not yet been published. Do not try to install from this repository yet.**

The intended package includes:
- The Pioneered-XZ skin and its assets
- The custom Pioneer DDJ-FLX4 controller mapping
- The SEARCH/X keyboard helper for an 800×480 touchscreen
- A patched `wvkbd-mobintl` using the Wayland **overlay** layer so it stays over fullscreen Mixxx
- An installer that configures labwc autostart and avoids overwriting the underlying StandaloneMixxx build

## Platform and compatibility

The existing tested touchscreen helper targets **800×480**, **Wayland/labwc**, and a touchscreen device identified as `generic ft5x06`. It currently needs adapting to users other than `/home/mix`. Raspberry Pi 4B 4GB is the intended public target; compatibility and installation on that hardware still need independent validation.

## Installation

First follow the setup guide in [StandaloneMixxx](https://github.com/ghztomash/StandaloneMixxx). Pioneered-XZ will be an add-on rather than a replacement for that build.

**Installation commands will be provided when the full v1.0 package and installer have been uploaded and verified.**

## Credits

Pioneered-XZ builds on these open-source projects:

- [timewasternl — Pioneered](https://github.com/timewasternl/Pioneered): original Pioneered Mixxx skin, forming the foundation of the touchscreen interface.
- [ghztomash — FLX-Mixxx](https://github.com/ghztomash/FLX-Mixxx): updated DDJ-FLX4 mapping forming the foundation of the controller integration.
- [ghztomash — StandaloneMixxx](https://github.com/ghztomash/StandaloneMixxx): Raspberry Pi standalone Mixxx environment that Pioneered-XZ is designed to complement.

Special thanks to these creators and the wider Mixxx community. The controller mapping also incorporates work credited in its source to Warker, nschloe, dj3730, jusko, Robert904, tomash_ghz and mikayla.fox.

Pioneered-XZ is an independently developed modification and extension of these projects.

## Development history

**v1.0** is the public release name for the working v136 keyboard baseline. This is a release renaming, not a functional change.
