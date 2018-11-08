---
title: "Version 5.7.1"
sidebar: katalon_studio_new_sidebar
permalink: katalon-studio/new/version-571.html
redirect_from:
    - "/display/KD/Version+5.7.1/"
    - "/display/KD/Version%205.7.1/"
    - "/x/mBTR/"
    - "/katalon-studio/new/version-571/"
description:
---

## LoopEdge 1.3.1 Release Notes<br>

### What's New in this Release?

The following enhancements and bug fixes are included in this software release.

Note that each item includes a reference number, such as [Edge-730], which is used for internal tracking purposes.

**What's New in this Release?**

* Upgrade Path
* DeviceHub
* Device Management
* Terminal User Interface (TUI)
* Known Issues

### Upgrade Path

* Upgrades using the .upd file are supported from version 1.0.3 (and later) to this current 1.3.1 version.
* After upgrading, take a LoopEdge backup.

### DeviceHub

1. &nbsp;The Device ID has been added to the IPSO topics or standard topics, to enable use of wildcards. [Edge-1189]
2. &nbsp;Additional registers have been added to Rockwell Allen-Bradley MicroLogix drivers. [Edge-1005]

### Device Management

1. LTE Modem Support was updated to prevent a duplicate APN (Access Point Name), when a custom APN is entered. [Edge-1236]

### Terminal User Interface (TUI)

1. The TUI was updated to include an option to configure a custom APN (Access Point Name) for an LTE modem. [Edge-1225]

### Known Issues

* TUI: Setting the time manually does not work even though it is present in TUI menus.
* Only select LTE modems/providers are supported. This has been tested with AT&T.
* Cloud connectors feature is still considered experimental and is in active development.