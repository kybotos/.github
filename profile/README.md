# Kybotos

Kybotos is a platform for running sandboxed WebAssembly apps on small music devices.
Apps reach the display, touch, audio, MIDI and a musical timeline (tempo, meter, scheduled notes) only through the Host API,
and the same `.wasm` runs on the ESP32-S3 device and on a Linux host.

- **[kybotos/kybotos](https://github.com/kybotos/kybotos)** — Host API, ESP32-S3 firmware, Linux host, the `appui` UI library, sample apps
  ([日本語の README](https://github.com/kybotos/kybotos/blob/main/README.ja.md))

Licensed under Apache-2.0. Apps that only use the Host API can be distributed under any license.
