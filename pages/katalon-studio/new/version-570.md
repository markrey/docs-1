---
title: "Version 5.7.0"
sidebar: katalon_studio_new_sidebar
permalink: katalon-studio/new/version-570.html
redirect_from:
    - "/display/KD/Version+5.7.0/"
    - "/display/KD/Version%205.7.0/"
    - "/x/tRTR/"
    - "/katalon-studio/new/version-570/"
description:
---

&nbsp;

## LoopEdge 1.3.0 Release Notes

### What's New in this Release?

The following enhancements and bug fixes are included in this software release.

Note that each item includes a reference number, such as [Edge-730], which is used for internal tracking purposes.

What's New in this Release?

* LTE Modem Support
* Device Discovery
* Cloud Service Integration
* DeviceHub Enhancements
* Device Management Enhancements
* Flows Enhancements
* Terminal User Interface (TUI) Enhancements
* Other Enhancements
* Known Issues

### LTE Modem Support

Cellular broadband connectivity is now supported so that gateways with modems can run as standalone devices. [Edge-1170]

1. Access LTE modem status and remote networks via the TUI. [Edge-1174]&nbsp;
2. Access LTE modem status via the Web UI on the device info page. [Edge-1172]&nbsp;
3. Device Discovery

A PLC device discovery service has been added in this release. This feature can be found under DeviceHub. [Edge-756]&nbsp;

### Cloud Service Integration

Connectors can now be created to communicate with the following cloud service providers:

* IBM Watson MQTT [Edge-1159]
* Microsoft Azure IoT Hub [Edge-1122, Edge-1066, Edge-840]
* Google Cloud IoT Core [Edge-1130]
* Generic MQTT Connector (for LoopCloud) [Edge-1132, Edge-1214]
* Loopback Connector (for performance testing) &nbsp;[Edge-1199]

### DeviceHub Enhancements

* A fix for the bulk upload of tags now handles OMA object IDs correctly. [Edge-1143]
* For the tag bulk upload, a count column has been added to the sample CSV file. This count is relevant only for certain device drivers, such as Siemens. [Edge-1160]
* For bulk-uploading of tags, when the PLC is a free tag device without predefined registers (such as Omron-NJ), if addresses are listed in the CSV file, an error message will indicate the issue. Free tag PLCs require register names exactly as defined in the PLC and no addresses are required. [Edge-1087]
* In the bulk-uploading CSV, the name column was changed to registerName to clarify the intent of the column. For backward compatibility, name can be used as the column header. [Edge-1079]
* Bulk download of all tags now correctly captures OMA object IDs. [Edge-1143]
* When deleting a device, you will be shown a warning, Deleting this device is irreversible, and you will be prompted to explicitly enter the name of the device. [Edge-1133]

### The following PLC device drivers have been enhanced to include multi-register support:

* Rockwell Allen-Bradley CompactLogix [Edge-930]
* Mitsubishi QJ71E71 ASCII [Edge-932]
* The following PLC device drivers are now supported:
* Koyo Click [Edge-1091]
* Mitsubishi R04 Ethernet Binary [Edge-1142]
* OPC UA [Edge-1173, Edge-1056]
* Panasonic FP Serial [Edge-1092]

The Tags table has been improved to effectively display more content. [Edge-1163]

* In the Tags page, a search box and a device filter with checkbox selections enable content filtering. [Edge-1102]
* Tag deletion now prompts you to confirm the deletion. [Edge-1071]
* Tag register types are now listed in all uppercase. [Edge-1117]
* A database number column has been added to the Tags page. [Edge-1197]
* Optional fields now can be configured when adding a register. &nbsp;[Edge-1201]

### Device Management Enhancements

1. DNS servers from DHCP take precedence over statically assigned DNS servers. On the LoopEdge Network page, the statically assigned DNS servers are listed as Fallback DNS Resolvers. [Edge-1145, Edge-1146]
2. A private/public key pair is created upon first boot of the device (RSA-2048 encryption algorithm). This key pair is used for device identification and certificates are created for this pair upon device activation. [Edge-1156, Edge-1157]
3. A custom Certificate now can be added to LoopEdge. [Edge-1106, Edge-1107]
4. A list of HID devices is now available in the UI. [Edge-1134]
5. The baud rate for serial ports is now displayed correctly. [Edge-1032]

### Flows Enhancements

1. The DataHub Publish and Subscribe nodes have swapped positions in the palette, to be consistent with other Input/Output nodes. [Edge-1083]
2. A Message Counter node as been added to the default Function nodes in the palette. [Edge-1082]

Terminal User Interface (TUI) Enhancements

1. Performance improvements have been made to the TUI. [Edge-1115]

### Other Enhancements

1. Support for FTPS has been added to the LoopEdge FTP service. [Edge-1194]
2. Improvements have been made to the labels in the Remote Access UI. [Edge-1154]

### Known Issues

* TUI: Setting the time manually does not work even though it is present in TUI menus.
* Only select LTE modems/providers are supported. This has been tested with AT&T.
* Cloud connectors feature is still considered experimental and is in active development.<br>&nbsp;