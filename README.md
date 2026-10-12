# JUUL Web — Device Companion (Clone)

Original, from-scratch Web Bluetooth companion page for JUUL2-style devices.

## Features
- Connect a JUUL2 over Web Bluetooth (HTTPS + Chrome/Edge desktop or Android required)
- Live battery / pod telemetry parsed from device notifications
- Lock and Find (ring) via authenticated JUUL2 commands — import your own credential JSON (stays local, never uploaded)
- GATT service/characteristic explorer with read / notify / write
- Hit-count statistics: today, 7-day, total, daily average, streaks, CSV export

## Usage
Open the GitHub Pages link below, tap **Connect JUUL**, shake the device until it pulses blue, then select it.

## Disclaimer
Unofficial, original-code clone. Not affiliated with JUUL Labs. Bluetooth identifiers used are factual values needed for interoperability. Device command opcodes were re-derived from observed traffic for interop; Ring/Lock need the official apps authenticated session credentials, which you provide yourself.
