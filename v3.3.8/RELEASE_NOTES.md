# Radar 1.28 v3.3.8

Released: November 9, 2026

## What's New

- Added a GitHub firmware download link and OTA download instructions to the web firmware update page.
- Redesigned the connected Wi-Fi screen with two clear steps: connect your phone to the displayed Wi-Fi network, then open the device's IP or .local address in a browser.
- Highlighted the instructions in yellow and underlined both web addresses. The .local address now uses the same larger font size as the IP address.
- The connection guide stays visible for 10 seconds and can be skipped with the device button. The web interface remains available during the countdown.
- Fixed countdown flicker by updating only small buffered text regions instead of redrawing the whole screen.
- Added bounded scrolling for long Wi-Fi names and .local addresses.
- Set the default radar location near Hong Kong International Airport. Existing custom locations are preserved; previously unconfigured (0,0) locations use the new default.
- Fixed leftover pixels when the weather CACHED indicator disappears after a refresh.

## OTA Firmware

- File: `radar-1.28-v3.3.8-ota.bin`
- SHA-256: `e72f96c0bdebad189b66200d6393b49f7310c6264708699ad2694782c0a64f79`
- Build revision: `048b1349`

This is an OTA upgrade file for compatible Radar 1.28 devices. Existing settings are preserved.
