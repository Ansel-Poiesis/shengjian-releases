<p align="right"><a href="guide.md">English</a> · <a href="guide.zh-CN.md">简体中文</a></p>

# FoilPage setup guide

[Back to the homepage](../README.md) · [Download the latest release](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) · [Report an issue](https://github.com/Ansel-Poiesis/FoilPage-releases/issues)

## Install and get started

1. Download the latest **FoilPage-Setup** installer from the official releases page and install it. FoilPage supports 64-bit Windows 10 version 1809 and later, and Windows 11.
2. Open FoilPage. In **Prepare**, sign in with an email code, check your environment, choose a save folder, and download a local model.
3. Paste a supported video link or import a local video or audio file.
4. Follow progress in **Tasks**. Read the source transcript and edit a separate draft in **Library**.

CPU transcription is available. The NVIDIA GPU pack is optional and must match the desktop version.

## Verify the installer

The installer is not currently signed with Windows Authenticode. SmartScreen may show a warning on first launch.

1. Confirm the installer came from the official FoilPage releases page.
2. Download the matching **SHA256SUMS.txt** file.
3. In PowerShell, run **Get-FileHash -Algorithm SHA256** on the installer and compare the result with that release's checksum file.
4. If the source and checksum match, you can choose **More info → Run anyway** if SmartScreen still appears. If they do not match, download the installer again.

A checksum checks file integrity; it is not a code signature.

## Local and cloud processing

Email-code sign-in identifies your account; no password is required. Local transcription runs on your PC and does not use cloud credits.

Hosted text cleanup and title tools are optional. The text used by an enabled cloud operation is sent to the selected service. Check the current in-app plan before using hosted services. Your own API is billed by its provider.

## Pair the browser extension

1. Open **Browser** in FoilPage and select **Open extension folder**.
2. In Chrome or Edge, open the extensions page and enable developer mode.
3. Choose **Load unpacked** and select the folder FoilPage opened.
4. Return to FoilPage, select **Allow connection**, then complete pairing in the extension within two minutes.
5. Open a supported video page and submit it from the extension.

The default folder is **%LOCALAPPDATA%\Programs\FoilPage\browser-extension**. An older installation may still use **%LOCALAPPDATA%\Programs\VideoToArticle\browser-extension**. Use the folder opened by FoilPage; do not move the installed extension manually.

## Connect an agent

Open **Settings → Agent control** to copy a full or read-only MCP configuration. The bundled CLI can manage documents, tasks, and the queue. Keep FoilPage running while an agent is connected.

## Local files and updates

Your media and documents belong to the current local data folder. Switching email accounts does not move them. The default folder is **%LOCALAPPDATA%\FoilPage**; older installations may migrate from **VideoToArticle**. Use the path shown by your current app.

If a document is missing after an update, check the selected data folder, filters, and archive state. Back up important files independently.

FoilPage follows the stable release channel by default. Check the [latest release](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) for current installers and notes.

## Content rights and support

Use FoilPage for content you have the right to access and process. Follow the terms of the source platform and the laws that apply to you.

For help, open an [Issue](https://github.com/Ansel-Poiesis/FoilPage-releases/issues) with your FoilPage version, Windows version, and reproduction steps. Remove private text, account details, verification codes, and signed media links from screenshots and logs.
