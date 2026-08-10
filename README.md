# HydraFlo firmware

Public OTA distribution repository for HydraFlo ESP32 firmware.

This repository contains only:

- `manifest.json`, read by HydraFlo devices;
- compiled `hydraflo.bin` files attached to GitHub releases.

Firmware source lives in the private `Lifasirko/hydraflo` repository. Wi-Fi
passwords, Telegram tokens, Chat IDs, setup passwords, Google URLs, and API keys
must never be committed here or embedded into release binaries.

Tagged builds in the private source repository create releases and update the
manifest automatically.
