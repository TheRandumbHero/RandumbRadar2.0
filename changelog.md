# RandumbRadar2 v2.0.0

This is the first stable release of RandumbRadar 2.0, bringing a complete redesign, new hardware support, and many quality-of-life improvements.

## New Features

- Support for multiple CYD display variants, ST7789 & ILI9341
- New GFX Library

## Aircraft Display

- Aircraft displayed using a new plane icon option.
- Plane icons rotate to match the aircraft's reported heading.
- Improved aircraft rendering and screen refresh.
- Improved handling of large numbers of nearby aircraft.
- User-selectable aircraft display limit.

## Customisation

- Radar Sweep added.

## User Interface

- Completely redesigned dashboard.
- New RandumbRadar branding.
- New boot logo.
- Updated boot and Wi-Fi setup screens.
- Improved sidebar layout.
- Cleaner settings and navigation.

## Web Dashboard

- Completely redesigned web interface.
- New responsive layout.
- Improved settings pages.
- Improved customisation pages.
- Firmware version displayed on the dashboard.
- Simplified navigation.

## OpenSky Improvements

- OAuth authentication support.
- Improved API handling.
- Automatic token management.
- 25-second refresh interval to remain within OpenSky Daily Free API usage limits.
- Improved aircraft filtering and sorting.

## Hardware

- Support for both original and newer CYD hardware revisions.
- Improved display initialisation.
- Improved touchscreen handling.
- Hold Boot to Reset Wifi rather than reflashing (All other Settings Saved)


## Improvements

- Major internal code cleanup.
- Improved performance.
- Reduced display flicker.
- More reliable aircraft updates.
- Numerous stability improvements and bug fixes.

## Fixes

- Fixed multiple display compatibility issues.
- Improved touch calibration.
- Improved radar rendering.
- Improved Wi-Fi setup process.
- Improved OpenSky connection reliability.
- Improved aircraft information display.
- Fixed various UI rendering issues.
- Fixed several display alignment issues.

## Known Issues

Two firmware builds are currently provided:

ST7789
ILI9341

Select the correct firmware for your display variant when flashing.

## Thank you!

Thank you to everyone who tested the beta releases and reported bugs.

# Roadmap
- OTA Updates - I had hoped to have this ready for this version, however with the two driver types it made it a tadge complicated so I will ensure this is working for the next release so only have to re-flash one more time.
