# OpenCore-Acer-E5-575

Acer E5-575 EFI folder for macOS Sequoia 15.7.5.

> **Note:** SMBIOS identifiers (`SystemSerialNumber`, `MLB`, `SystemUUID`, and `ROM`) in `EFI/OC/config.plist` have been scrubbed with placeholder values. Generate your own using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) before signing into Apple Services.

## Specs

| Component          | Model                     |
|---------------------|---------------------------|
| CPU                 | Intel Core i3-6006U       |
| iGPU                | Intel HD Graphics 520     |
| Wi-Fi / Bluetooth   | QCA9377                   |
| Ethernet            | Realtek RTL8168           |
| Audio               | Realtek ALC255            |

## What's Working / Not Working

| Component                                | Status   | Notes                                                                 |
|------------------------------------------|----------|-----------------------------------------------------------------------|
| GPU Acceleration                         | Working  |                                                                       |
| Audio (speakers)                         | Untested |                                                                       |
| Audio (headphone jack)                   | Working  |                                                                       |
| Microphone                               | Working  |                                                                       |
| Ethernet                                 | Working  |                                                                       |
| Wi-Fi                                    | Working  | Requires [Ath10k-Connectivity](https://github.com/jonasw8/Ath10k-Connectivity) app |
| Bluetooth                                | Working  |                                                                       |
| Touchpad                                 | Working  | Enable Tap to Click & Drag Lock                                       |
| Keyboard                                 | Working  |                                                                       |
| Function keys (brightness/volume/media)  | Working  |                                                                       |
| Fan control                              | Partial  | Managed via [SMCAcerFan](https://github.com/misternear/SMCAcerFan)    |
| USB ports                                | Working  |                                                                       |
| Sleep                                    | Working  |                                                                       |
| Shutdown / restart                       | Working  |                                                                       |
| Battery percentage                       | Working  |                                                                       |
| Webcam                                   | Working  |                                                                       |
| SD card reader                           | Untested |                                                                       |
| HDMI (video)                             | Untested |                                                                       |
| HDMI (audio)                             | Untested |                                                                       |
