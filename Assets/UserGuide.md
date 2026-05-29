# HM Remote — User Guide

Version 0.9

*29 May 2026*


## Database generation

1. Insert the SD card into a card reader (**recommended**) or connect the player via USB.

Scanning through a card reader is significantly faster than scanning through the player.

2. Select the drive.

Drives connected through the player are marked as `(player)`.

3. Press **Generate**.

4. Wait until scanning completes.

5. The last generated database is loaded automatically when HM Remote starts.


## Incremental scan

When enabled, HM Remote updates only changed files.

New files are added automatically.

Deleted files are removed automatically.

Disable incremental scan only if you want to rebuild the database from scratch.



## Artwork

HM Remote searches for album artwork in this order:

1. Image file in the album folder
2. Embedded artwork inside audio files

Recommended filenames:

- `cover.jpg`
- `folder.jpg`
- `front.jpg`

Artwork size affects database size and image quality:

- **Without** — fastest generation, smallest database
- **Small** — compact database
- **Standard** — balanced quality and size
- **Big** — better artwork quality
- **Maximal** — highest artwork quality, largest database


## QR transfer

1. Generate a database.

2. Press **Generate QR**.

3. Scan the QR code using the mobile app.


## Playback control

Connect to the player and use:

- Previous
- Play / Pause
- Next
- Volume

Current track, codec information and battery level are shown in the status bar.


## Device menu

Device provides:

- **Connect / Disconnect**  
Connects to or disconnects from the player.

- **LED control**  
Turns off the Bluetooth status LED which may be distracting during night listening.

- **Power off**  
Turns the player off remotely.

- **Device information**  
Displays device information.
