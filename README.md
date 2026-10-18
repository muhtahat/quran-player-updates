# Quran Player updates

Firmware downloads for gift devices built with an ESP32-S3 N16R8 and NS4168 amplifier.

- Install the initial firmware locally once before giving the device away.
- Join QuranPlayer-Setup to enter the recipient's WiFi details. Open http://quranplayer.local/ on that WiFi.
- In Settings, automatic updates can be enabled or disabled. Devices download signed releases over HTTPS when idle. No GitHub account is needed on a player.
- Settings, the SD card and local audio are preserved by internet application updates.
- Only this hardware model is supported.

## Downloads

Use Releases for firmware.bin (application update), manifest.txt (signed metadata), and initial-install.bin when provided (blank-board installation at address 0x0). The full initial image resets a configured device; use the application updater for an existing player.

Do not publish passwords, access tokens, private signing keys, device backups or home configuration here. Source code is maintained separately.
