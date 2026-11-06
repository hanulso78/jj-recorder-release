# JJ Recorder

A screen recorder for Windows. Record your screen, games and audio, take screenshots, and make quick edits to your recordings, all in one small program.

**[Download the latest version](https://github.com/hanulso78/jj-recorder-release/releases/latest)**

![JJ Recorder home screen](screenshots/home.png)

This repository only hosts the release files. Each release contains a zip file with the program, documentation and license information.

## Features

**Recording**
- Full screen, a selected area, a window (even when covered by other windows), games and capture devices
- Audio only recording
- GPU encoders (NVIDIA, Intel, AMD) and the encoders built into Windows, so recording uses little CPU
- OpenH264 for H.264 on the CPU, even on a PC without a graphics card encoder (downloaded from Cisco the first time you choose it)
- Installed VfW codecs such as x264vfw, x265vfw and Xvid can also be used
- Crash-safe MP4: if the PC stops during recording, the file still plays up to that point
- Select Window can also pick a panel, list or input box inside a window
- Time limit, size limit, automatic file splitting and scheduled recording

**Audio**
- System sound and microphone together, with an optional separate microphone track
- Microphone noise reduction and automatic level boost for quiet voices
- A warning on the REC badge if the microphone stops sending sound during a recording
- Spoken or sound cues when recording starts, stops and pauses

**On screen**
- Draw on the screen while recording, and zoom in around the cursor
- Click highlights, cursor spotlight and keystroke display
- Webcam overlay with green or blue background removal (drag it in the preview to set its position and size), and logo overlay

**Screenshots**
- Screenshots, timed captures and scrolling capture of long pages
- Copy text from the screen (OCR) with the OCR built into Windows, or with PaddleOCR, which reads screen text more accurately (downloaded the first time you choose it)
- Image editor with arrows, callouts, numbered stamps, blur, mosaic, cropping and more. It opens right after a capture (you can turn this off)

**Editing recordings**
- Trim, save as GIF, reduce file size, change playback speed, normalize loudness, extract audio and join files

Available in English, Korean, Japanese and Chinese.

## Screenshots

**Video settings**: frame rate, quality with an estimated file size, encoder and overlays. Drag the webcam in the preview to place it

![Video settings](screenshots/video.png)

**Audio settings**: system sound and microphone, noise reduction and volume

![Audio settings](screenshots/audio.png)

**General settings**: save location, file names, time limits, scheduled recording and language

![General settings](screenshots/general.png)

**Image editor**: numbered stamps, blur, arrows and callouts on a screenshot

![Image editor](screenshots/editor.png)

## Requirements

- Windows 10 (version 1903 or later) or Windows 11, 64-bit

## Install

1. Download `jj-recorder-<version>.zip` from the [latest release](https://github.com/hanulso78/jj-recorder-release/releases/latest).
2. Unzip it to any folder you can write to, for example `Documents\JJ Recorder`.
3. Run `jj-recorder.exe`. No installation is needed.

Press **F1** in the program to open the manual.

## Update

The program checks for a new version once a day when it starts, and marks the **Update** menu when one is available. You can turn this off on the **Update** page.

To update, open **About > Update** and click **Check for updates**. If a new version is available, click **Update now**. The program downloads it, checks its signature and restarts. Your settings are kept.

You can also download the new zip and unzip it over the old folder.

## Uninstall

Close the program and delete its folder. Settings are stored in `%LOCALAPPDATA%\jj-recorder`; delete that folder too if you want to remove them.

## Privacy

JJ Recorder does not collect or send any usage data. It connects to the internet only to:

- Check for and download updates from this GitHub repository (once a day when it starts, or when you click **Check for updates**; the daily check can be turned off)
- Download the PaddleOCR files from this repository, when you choose PaddleOCR
- Download OpenH264 from Cisco's server, when you choose OpenH264

## License

JJ Recorder uses open source libraries such as Qt and FFmpeg under the LGPL. The list of libraries and their license texts are in `THIRD-PARTY.txt` and the `licenses` folder inside the zip. `SOURCE-OFFER.txt` explains how to get the source code of the LGPL libraries.

## Support

JJ Recorder is free to use. If it is useful to you, you can support its development:

- **GitHub Sponsors** (card, monthly or one time): https://github.com/sponsors/hanulso78
- **Bank transfer in Korea**: KakaoBank `3333346492333` (민인학)

## Contact

Questions and feedback:

- Support board: https://groups.google.com/g/jj-recorder
- Email: inhak.min@gmail.com

The **Contact** and **Donate** pages at the bottom of the program's sidebar have the same information.
