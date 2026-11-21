# Keyness

Keyness is a lightweight keyboard lock indicator for Linux Wayland desktops.

It displays an on-screen notification when Caps Lock or Num Lock changes state.

## Features

- Caps Lock indicator
- Num Lock indicator
- Neutral indicator when a lock is off
- Native C implementation for KDE Plasma
- Native Wayland layer-shell overlay for KDE Plasma
- GNOME Shell extension integration
- Automatic notification fade-out
- Automatic desktop startup

## Desktop Support

Keyness supports multiple Wayland desktop environments through desktop-specific integrations.

- **KDE Plasma:** Uses a native C implementation with Wayland layer-shell.
- **GNOME:** Uses a GNOME Shell extension with native GNOME interfaces.

## Requirements

- Linux desktop running Wayland
- KDE Plasma with wlr-layer-shell support, or
- GNOME Shell 49 or compatible supported version

## Privacy

Keyness runs locally on your computer. It reads Caps Lock and Num Lock status to display notifications.

Keyness does not collect personal information, log keystrokes, use analytics, or transmit data over the internet.

## Project Status

**Version:** 0.1.1-2

The current release supports Caps Lock and Num Lock on KDE Plasma and GNOME.

## License

Keyness is proprietary software. It is free for personal, non-commercial use only.

Commercial use, modification, and redistribution require prior written permission from the copyright holder.

See the LICENSE file for the complete terms.

## Publisher

UPSIDE

-----DOWN

UNDER
