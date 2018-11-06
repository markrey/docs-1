---
title: Version 1.1.0
sidebar: katalon_studio_new_sidebar
permalink: katalon-studio/new/version-55.html
redirect_from:
  - /display/KD/Version+5.5/
  - /display/KD/Version%205.5/
  - /x/jAnR/
  - /katalon-studio/new/version-55/
description:
---

## General Enhancements

Added a timezone search field and added the ability to set the timezone. [Edge-837, Edge-595]

Hostnames, in addition to IP addresses, are displayed in the UI. [Edge-730]

Memory and storage data is represented with new charts. [Edge-818]

Configurable host setting (Hostname, DNS, NTP, Timezone). [Edge-788, Edge-789, Edge-798]

Firmware version info is reported correctly. [Edge-804, Edge-799]

Fixed an issue where the IP address was not always correct after a firmware upgrade. [Edge-805, Edge-802]

Fixed cloud activation and refresh issues. [Edge-806, Edge-832]

Improvements have been made to the networking stack. [Edge-778]

UI prevents duplicate device names. [Edge-793]

Improved display on the network configuration page. [Edge-862]

The end-user license agreement (EULA) requires acceptance for first-time logins. [Edge-899, Edge-895, Edge-911, Edge-938, Edge-896]

The Intercom feature for contacting support has been enhanced. [Edge-892]

The Remote Access page now includes a Copy option. [Edge-919]

UI forms are submitted when the Enter key is pressed. [Edge-925]

Default topics are no longer listed in the Stats page. [Edge-920]

Certificate install issues have been resolved. [Edge-869, Edge-845]

User roles can now be changed and a user with an observer/developer role can no longer see the add/remove options. [Edge-842, Edge-883]

Device cards displayed in the Firefox browser now render correctly. [Edge-901]

Device status display issues were fixed. [Edge-856]

Tooltips have been added to many of the UI main elements, enabling quick access to help. [Edge-753]

DataHub system connectors are not included in backup/restore. [Edge-959]

Decreased the time it takes to initially load the application in the browser. [Edge-968]

The Device Management page now displays the activation status. [Edge-960]

Hostinfo and net info data is polled to ensure updated information is displayed. [Edge-874]

Data type conversion has been implemented for registers. The UI takes decimal input and converts it to the relevant octal or hexadecimal format. [Edge-957]

ID columns in various screens were removed because the IDs are relevant only for internal processing. [Edge-974]

When DataHub raw subscription is successfully updated, the status is correctly displayed. [Edge-951]

DeviceHub and DataHub

Export DeviceHub tags as a CSV file. [Edge-661]

CSV format is displayed in DeviceHub. [Edge-768]

PollOnce topic added to the DeviceHub tag action list. [Edge-798]

Backup/Restore now includes DeviceHub and sensonodegold. [Edge-761, Edge-820, Edge-30]

DeviceHub drivers fix: added Rockwell driver dependencies. [Edge-782]

Driver name is included in the device card, along with the ability to copy it. [Edge-767]

DeviceHub device cards now display long text strings correctly. [Edge-814]

Fixed an issue where the raw topic could not be copied from the DeviceHub Tags page. [Edge-831]

Support for additional drivers in DeviceHub: Mellanox drivers for 10GB ethernet included. [Edge-825]

For OMA binding, changed the instance ID type to string. [Edge-766]

DataHub improvements prevent duplicate connections with the same client ID. [Edge-796]

DataHub UI improvements handle smaller screen resolutions. [Edge-428]

DataHub prevents creation of raw topics with duplicate names. [Edge-797]

DeviceHub data type case sensitivity is reconciled in the CSV file for bulk-loading tags. [Edge-908]

DeviceHub display paging has been improved. [Edge-847]

DeviceHub no longer starts polling when there are no devices. [Edge-861]

When adding a Device, the device name is mandatory. &nbsp;[Edge-836]

DataHub cloud connector deletion no longer waits for the poll status to finish. [Edge-849]

DataHub raw topics for a cloud connector can now be deleted. [Edge-853]

Hostinfo now returns the IPv6 gateway address. [Edge-890]

Prior to this release, a device could fail after running for several minutes. This feature has been stabilized. [Edge-942]

A device can now be deactivated once it has been activated in LoopCloud. [Edge-909]

Time warning messages no longer overlap each other. [Edge-860]

Driver performance has been improved. [Edge-792]

DeviceHub Tags page now includes a Download Tags action. [Edge-921]

DeviceHub Tags actions had minor text improvements. &nbsp;[Edge-900]

Improved spacing has been added to the Tags page. [Edge-859]

Performance for a large number of tags (10k+) has been improved. [Edge-848]

Bulk-loading of tags can now handle a CSV with more than 20k tags. [Edge-967]

Application/Marketplace

Application uninstall has additional confirmation checks. [Edge-816]

Registry tag-loading issues have been resolved. [Edge-922]

## System

Software update lists only relevant files. [Edge-801]

Software updates remove relevant files after a successful upgrade, to reclaim space. [Edge-821]

Improvements have been made to the Backup/Restore feature. [Edge-907, Edge-893, Edge-855]

Enabled support for additional devices in the kernel (USB-to-serial, HIDRAW). [Edge-913]

Serial cables are detected as expected. [Edge-890]

Hostname is set on first boot. [Edge-889]

## Terminal User Interface (TUI)

A new version of the TUI includes the following enhancements:

The terminal user interface (TUI) now works over a serial line. [Edge-902, Edge-894]

New screens have been added: Info, Setup, Wlan. [Edge-828, Edge-867, EDGE-948]

New configurations include: country, DNS, time, password change, language selector. [Edge-876, Edge-877, EDGE-878, EDGE-885]

Ethernet interfaces can now be configured. [Edge-868]

LoopCloud activation/deactivation has been added. [Edge-879]

License activation/deactivation has been added. [Edge-880]

Reboot/shutdown has been added. [Edge-881]

Login authentication has been added. [Edge-884]

## Known Issues

TUI: Setting the time manually does not work even though it is present in TUI menus