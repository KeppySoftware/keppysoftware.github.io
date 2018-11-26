## What's "Keppy's Software"?
This is the name I use for publishing my software, targeted towards professionals.

## Projects
### OmniMIDI
OmniMIDI *(Formerly known as Keppy's Synthesizer)* is a MIDI driver for professional use.<br />
It is a fork of the original [BASSMIDI Driver](https://github.com/kode54/BASSMIDI-Driver) by Kode54.

Its main features are:
- Support for multiple audio APIs. *(DirectX Audio, WASAPI and ASIO)*
- Distributes the workload of the MIDI events parser and audio renderer on multiple threads, to ensure speed and responsiveness on the worst case scenarios.
- Clean and easy-to-use UI. No gimmicks that might distract the user from their objective.
- Constant updates, to keep the driver fresh and always up-to-date to users requests.

Source code: [OmniMIDI source](https://github.com/KeppySoftware/OmniMIDI)<br />
Releases: [OmniMIDI releases](https://github.com/KeppySoftware/OmniMIDI/releases)

### Keppy's MIDI Converter
Keppy's MIDI Converter *(Formerly known as Keppy's Spartan MIDI Converter)* is a freeware, fully functional MIDI to WAV converter.

Its main features are:
- It's **FREE**, unlike most other converters.
- Clean and easy-to-use UI. No gimmicks that might distract the user from their objective. Just like OmniMIDI!
- Ships with LoudMax, which prevents the audio from clipping.
- Support for VST instruments.

Source code: [KMC source](https://github.com/KeppySoftware/KMC)<br />
Releases: [KMC releases](https://github.com/KeppySoftware/KMC/releases)

### KDMAPI
An extension of OmniMIDI's engine.<br />
It allows developers to directly interface their application with the driver, to get rid of the latency and unresponsiveness introduced by Windows Multimedia.

Guide: [Official KDMAPI documentation](https://github.com/KeppySoftware/OmniMIDI/blob/master/DeveloperContent/KDMAPI.md)<br />
Developer content: [Developer content](https://github.com/KeppySoftware/OmniMIDI/tree/master/DeveloperContent)

### Windows Multimedia Wrapper
A replacement for WINMM, which allows non-KDMAPI applications to make use of the API.<br />
KDMAPI will **only** work with OmniMIDI.

Source code: [WinMMWRP source](https://github.com/KeppySoftware/WinMMWRP)<br />
Releases: **Built into OmniMIDI's configurator**

### Contact me
Do you need help? Contact me via e-mail or Discord.

E-mail: [kaleidonkep99@outlook.com](mailto:kaleidonkep99@outlook.com)
Official Discord server: [Keppy's Software - Feedback Server](https://discord.gg/73DVswT)
