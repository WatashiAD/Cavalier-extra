# Cavalier-extra

This is a fork of [NickvisionApps/Cavalier](https://github.com/NickvisionApps/Cavalier) by **WatashiAD** with additional customization options.

## Changes from upstream

* **Foreground image behind visualization** — foreground image renders behind the bars/wave (clipped to the drawing area) instead of on top, for all drawing modes.
* **Full CAVA input control** — choose audio input method (pulse/pipewire/alsa/fifo/sndio/portaudio) and source directly from the UI instead of environment variables.
* **Waves toggle** — enable/disable the CAVA wave effect across bars.
* **Gravity control** — slider to set how fast bars fall (0–200).
* **8-band equalizer** — adjust frequency response per band (0–2x).
* **Fine-grained sensitivity** — sensitivity slider now starts at 1 with step 1 (was 10 step 10).
* **Fixed Colors & Images pages** — wrapped content in `Adw.PreferencesGroup` to comply with Libadwaita child requirements.
* **.NET 10** — updated target framework from .NET 8 to .NET 10.

## Original features

* 11 drawing modes!
* Set any single color, a gradient or an image for background and foreground.
* Full CAVA configuration: framerate, bars, sensitivity, smoothing, noise reduction, and more.

## Installation

Build from source with .NET 10:

```
dotnet build
dotnet run --project NickvisionCavalier.GNOME
```

### Dependencies

- [.NET 10](https://dotnet.microsoft.com/en-us/)
- [CAVA](https://github.com/karlstav/cava/) >= 0.9.1

## Upstream

Original project: [NickvisionApps/Cavalier](https://github.com/NickvisionApps/Cavalier)

## Screenshots

Hyprland

All Screenshots are from Hyprland.
