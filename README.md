# OnAirMic

OnAirMic is a free macOS app that turns your Mac into a small radio station. Build programs from
audio clips and voice scripts, schedule them, and OnAirMic broadcasts them through a virtual
microphone, “OnAirMic”, that browsers, Zoom, OBS and other apps can choose as their input.

## Download

Get OnAirMic at **[onairmic.com](https://onairmic.com)**, or download the latest version directly:
[onairmic.com/download](https://onairmic.com/download).

OnAirMic requires macOS 26 or later. Every release is signed with Apple's Developer ID and
notarized by Apple.

## Updates

OnAirMic keeps itself up to date with [Sparkle](https://sparkle-project.org):

- It checks for a new version once a day, using the update feed at
  `https://onairmic.com/appcast.xml` (the [`appcast.xml`](appcast.xml) in this repository).
- To check now, choose **OnAirMic › Check for Updates…**, use **Settings › Updates › Check Now**,
  or right-click the OnAirMic item in the menu bar.
- In **Settings › Updates** you can turn off automatic checks, or let OnAirMic download and install
  updates by itself.
- Every update is signed twice: with OnAirMic's update key (EdDSA) and with Apple's Developer ID.
  OnAirMic checks both before it installs anything.
- When an update includes a newer virtual microphone, **Settings › Virtual microphone** offers
  **Update Driver…**.

Versions before 1.0.0 (10) can't update themselves. If you have one of those, download OnAirMic
once from [onairmic.com](https://onairmic.com); later versions then update automatically.

## About this repository

This repository only publishes OnAirMic: the update feed (`appcast.xml`) and the
[Releases](https://github.com/xploredatum/onairmic-releases/releases) with the disk images. It
contains no source code.

© 2026 XPLOREDATUM TECHNOLOGIES LLP · [onairmic.com](https://onairmic.com)
