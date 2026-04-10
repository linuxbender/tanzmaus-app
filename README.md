# MFB Tanzmaus Sample Manager App

A web-based sample manager for the MFB Tanzmaus drum machine.

![Tests](https://linuxbender.github.io/tanzmaus-app/badge-tests.svg)

🌐 **[Open App](https://linuxbender.github.io/tanzmaus-app/)**

## Requirements

- Browser with Web MIDI API support (Chrome or Edge)
- MFB Tanzmaus with **[firmware ≥ 1.6](https://github.com/linuxbender/mfb-backup/tree/main/Tanzmaus/firmware)**
- Connect MFB Tanzmaus (Midi In) to your Midi interface (Midi Out) using a standard MIDI cable
- Open the app in your browser (Google Chrome) and select the correct MIDI interface from the dropdown menu
- Red / Real is not active, LEDs is not light up, otherwise the app will not work
- Sequencer must be stopped, otherwise the app will not work
- use a standard midi interface - transmitting MIDI data is slow

## Features

- Upload samples to any of the 32 slots (Bank 1 & 2, Slots 1–16)
- Sample Manager: drag & drop, batch upload, preview playback
- Export / Import project as JSON backup
- Load factory default samples

## Disclaimer

Use of this app is at your own risk, without any warranty that it will work correctly.
The authors are not responsible for any damage to your device.

## License

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)
