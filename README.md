# OpenCore-Acer-E5-575

Acer E5-575 EFI folder for macOS Sequoia 15.7.5.

## Specs

| Component          | Model                     |
|---------------------|---------------------------|
| CPU                 | Intel Core i3-6006U       |
| iGPU                | Intel HD Graphics 520     |
| Wi-Fi / Bluetooth   | QCA9377                   |
| Ethernet            | Realtek RTL8168           |
| Audio               | Realtek ALC255            |

## What's Working / Not Working

| Component                              | Status  | Notes                     |
|------------------------------------------|---------|----------------------------|
| GPU Acceleration                       | Working  |                            |
| Audio (speakers)                       | Untested |                            |
| Audio (headphone jack)                 | Working  |                            |
| Microphone                             | Working  | Audio may becomes muddy    |
| Ethernet                               | Working  |                            |
| Wi-Fi                                  | Broken   | No Kext For QCA9377        |
| Bluetooth                              | Broken   | No Kext For QCA9377        |
| Touchpad                               | Working  | Enable Tap to Click & Drag Lock       |
| Keyboard                               | Working  |                            |
| Function keys (brightness/volume/media)| Partial  | Mismatch brightness keys   |
| USB ports                              | Working  |                            |
| Sleep                                  | Partial  | Audio becomes muddy        |
| Shutdown / restart                     | Working  |                            |
| Battery percentage                     | Working  |                            |
| Webcam                                 | Working  |                            |
| SD card reader                         | Untested |                            |
| HDMI (video)                           | Untested |                            |
| HDMI (audio)                           | Untested |                            |
