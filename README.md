# Minimalist Solar System Widget

A beautiful, hardware-accelerated top-down planetary orbit tracking widget designed for the [Übersicht](https://github.com) Mac ecosystem. Features a glowing solar yellow/orange sun with planets revolving at true proportional astronomical velocities.

## Visual Styling
- Custom position alignment optimized for desktop centering.
- Pure CSS hardware-accelerated keyframe animation logic (ultra-low CPU overhead).
- Universal theme compatibility matching dark and cyber aesthetics.

## Installation Instructions

1. Download or clone this repository folder.
2. Ensure the folder is named exactly `my-solar-system.widget`.
3. Move the folder directly into your native Übersicht widgets directory:
   `~/Library/Application Support/Uebersicht/widgets/`
4. Click the Übersicht app icon in your Mac menu bar and select **Refresh All Widgets**.

## Adjusting Position
To shift the alignment higher or lower to fit your specific wallpaper setup, open `index.jsx` and modify the vertical pixel calculation near the top:
```css
transform: translate(-50%, calc(-50% + 280px)); /* Change 280px to fit your display layout */
```
