<p align="center">
  <img src="Assets/logo.svg" width="64">
</p>

<h1 align="center">HM Remote</h1>

<p align="center">
Desktop remote control and database management tool for *HiFiMAN HM1000* and *HM901R* players.
</p>

<p align="center">
  <img src="Assets/Screenshots/main-window.png" alt="HM Remote Main Window">
</p>

## Overview

HM Remote is a desktop application for remote control and music database management for __HiFiMAN HM1000__ and __HM901R__ players.

The project combines advanced playback control, music library navigation and database management in a single application. HM Remote allows you to control playback, browse your music collection, manage the playback queue and maintain player databases without relying on the official HiFiMAN PC Assistant.

## Remote Control

HM Remote provides a complete set of essential remote control functions:

* Play / Pause
* Previous / Next Track
* Volume Control
* Track Seek Bar
* Connect / Disconnect Player
* Remote Power Off
* Bluetooth LED On / Off

### Music Library

HM Remote allows you to browse the player's music library and start playback directly from the application:

* Browse music library by folders, artists, albums and years
* Start playback directly from the library
* Display current track information
* Display album artwork

### Playback Queue

* Add albums to the playback queue
* Replace the current queue with a selected album
* Remove tracks from the queue
* Reorder tracks within the queue
* View the current playback queue

### Player Status

* Battery level indication
* Charging status indication

## Database Management

HM Remote provides the complete functionality of the official HiFiMAN PC Assistant while extending it with additional features.

Supported features include:

* Create new databases
* Load existing databases
* Browse database contents
* Delete databases
* Generate QR codes for player import
* FAT32 and exFAT support

### Incremental Database Updates

There is no need to rebuild an entire database every time your music collection changes.

HM Remote can update existing databases incrementally by analyzing changes and updating only affected entries. This significantly reduces processing time for large music libraries.

The application can work with memory cards installed in the player as well as cards connected directly through a card reader. Direct card access can dramatically reduce scanning and database generation times, especially when working with large collections.

Database scanning and generation can be cancelled at any time without waiting for the entire process to complete.

### Artwork Handling

HM Remote supports external album artwork.

During scanning, the application searches for artwork files in the album folder before falling back to embedded artwork, eliminating the need to embed the same image into every audio file.

Users can choose the size of generated artwork during database creation.

## A Modern Replacement for PC Assistant

HM Remote provides the complete functionality of the official HiFiMAN PC Assistant while adding full-featured desktop remote control.

The project was designed as a single application for HM1000 and HM901R owners, combining playback control, music library navigation and database management.

## Requirements

* Windows 10/11 x64
* Microsoft .NET 8 Desktop Runtime (x64)

## Download

The latest version is available on the Releases page.

## Support the Project

HM Remote is a free non-commercial project developed in spare time.

If you find the software useful and would like to support further development, donations are welcome.

The next major goal is a dedicated __iPhone__ and __iPad__ application. This would allow the project to replace HiFiMAN's outdated mobile software ecosystem and provide a foundation for future features and improvements.

With sufficient community interest and support, an __Android__ version may follow.

### PayPal

https://paypal.me/finvarg

### Bitcoin (BTC)

bc1qy2fvxxvdmepyy0rhq642g36elx206u9f8fcff9

### USDT, USDC, ETH (ERC-20)

0x4eD9462a071d51C54BdaF63de5a1d7DACd4A6245
