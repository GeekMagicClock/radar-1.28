# Radar 1.28 v3.3.2

Released: October 4, 2026

## What's New

- Added verified local radar and weather caches for faster startup and screen switching.
- Cached content is shown first, followed by a delayed network refresh.
- Fixed occasional false “Weather unavailable” messages after leaving the radar screen.
- Weather-to-radar switching now restores the retained radar frame before connecting to the data service.
- Chinese high/low labels now use localized characters.
- Improved invalid-callsign filtering.
- Reduced radar-cache write frequency to protect flash storage.

## OTA Firmware

- File: `radar-1.28-v3.3.2-ota.bin`
- SHA-256: `b3b3d068653026a079b77a8eb0d01cf672eef86428e754888bcd08fbff26d2ee`
- Build revision: `690adefe`

This is an OTA upgrade file for compatible Radar 1.28 devices. Existing settings are preserved.
