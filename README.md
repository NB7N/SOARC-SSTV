# SOARC-SSTV-
SOARC Software Suite SSTV Android App
# SOARC SSTV

**SOARC SSTV** is an Android application for sending and receiving Slow Scan Television (SSTV) images using amateur radio.

The app is being developed for the **Southern Oregon Amateur Radio Club (SOARC)** with an emphasis on a clean mobile interface, practical field use, and compatibility with common amateur-radio SSTV equipment and applications.

## Features

- Live SSTV receive and image decoding
- Automatic SSTV mode detection
- Robot 36 receive and transmit support
- Support for multiple common SSTV modes
- Live waterfall display
- RX audio-level meter
- Continuous live receive monitoring
- Send images from the phone camera or gallery
- Rotate and preview images before transmission
- Bluetooth audio support for compatible radios
- VOX-friendly transmit lead-in
- Adjustable transmit audio level
- Save SSTV transmissions as WAV files
- Separate Morse-code station ID transmission
- Configurable amateur-radio callsign
- Multiple display themes
- Automatic screen-awake option during operation
- Engineering diagnostics available when enabled in Settings

## Bluetooth Radio Operation

SOARC SSTV can route transmit audio through Android Bluetooth communication audio.

Bluetooth audio by itself does not provide a universal radio PTT command. Depending on the radio, transmission may require:

- Radio VOX
- Manual PTT
- Compatible Bluetooth headset/PTT control
- A wired audio/PTT interface

The app includes transmit timing intended to allow VOX-equipped radios time to key before SSTV data begins.

## Receiving SSTV

Open the **Receive** screen and start listening.

The app monitors incoming audio, searches for SSTV synchronization and mode information, and begins constructing the received picture when a supported signal is detected.

Robot 36 has been a primary development and testing mode.

## Sending SSTV

From the **Send** screen:

1. Select a picture from the gallery or camera.
2. Rotate or adjust the image if needed.
3. Select the SSTV mode.
4. Select the desired audio output method.
5. Verify radio audio/PTT or VOX operation.
6. Transmit the picture.

A transmission can also be saved as a WAV file for testing or external playback.

## Station Identification

The operator callsign can be configured in **Settings**.

New installations default to:

`URCALL`

A separate Morse ID function is available so station identification does not interfere with the SSTV image transmission.

## Media Files

SOARC applications use the common media family:

`SOARC Radio Suite`

SSTV images and related files are stored using SOARC-specific filenames where practical.

## Building the Android App

The project includes:

`BUILD_ANDROID.bat`

On Windows, extract the project and run the build file.

Successful builds place the release files in the:

`RELEASE`

folder.

Typical release files include:

- `SOARC-SSTV.apk` — Android installation package
- `SOARC-SSTV.aab` — Google Play Android App Bundle
- README and release documentation

The build system automatically reuses the same local application signing identity so future APK versions can normally be installed as upgrades.

## Project Status

SOARC SSTV is under active development.

Receive and transmit functions are being tested with real Android devices, SSTV software, and amateur-radio equipment. Additional decoder refinement, radio compatibility testing, UI polish, and SSTV-mode validation are ongoing.

Feedback and real-world testing are welcome.

## Amateur Radio

Users are responsible for operating in accordance with the amateur-radio regulations applicable to their country, license class, frequency, mode, and equipment.

## Southern Oregon Amateur Radio Club

More information about SOARC:

https://www.soarc.org/

## Credits

**SOARC SSTV**

Copyright NB7N - Beaner Industries in association with Jack Ruby Productions.

Developed as part of the **SOARC Radio Suite**.
