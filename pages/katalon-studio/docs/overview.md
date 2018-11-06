---
title: "Overview"
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/overview.html
redirect_from:
    - "/display/KD/Overview/"
    - "/display/KD/Overview/"
    - "/x/oArR/"
    - "/katalon-studio/docs/overview/"
description:
---

LoopEdge is an operating system on an Industrial PC (IPC) appliance. See Why LoopEdge is a Whole OS This edge-level software seamlessly collects data from IoT devices/systems (such as sensors and PLCs) and integrates the data into the cloud or into on-premise enterprise systems. Extensive knowledge of 35+ device drivers, both legacy and newer systems, enables LoopEdge to manage the variety of devices in an industrial environment. LoopEdge software provides support for many protocols/buses (RS232, RS485, CAN, Ethernet, Fieldbus, etc.) via an IPC appliance that is connected to the Internet. The raw or processed data can be visualized and analyzed at the edge or sent to LoopCloud, near real time.

What are the LoopEdge Advantages?

Device Connectivity

Cloud Connectivity

Application Deployment

Management

LoopEdge Architecture

How do I access LoopEdge?

LoopEdge Network Diagram

Let's get started...

What are the LoopEdge Advantages?

Simply stated, LoopEdge has these main functions:

Enable secure data collection from any industrial device.

Send data securely to the cloud.

Run applications on top of the data.

Manage devices.

Device Connectivity

LoopEdge enables collection of data from assets while overcoming the following challenges:

Collection from both legacy and modern systems

Security

Big data needs filtering

Analytics need to sift through data to display actionable data

Cloud Connectivity

LoopEdge Cloud Connectors enable easy integration with the LoopCloud platform for data visualization and device management. Leverage data collected at the edge and make it available in the cloud for real-time monitoring and machine learning.

Application Deployment

To get the most out of collected data, both public and private marketplace repositories enable integration with enterprise applications and databases. Drive business intelligence with data-driven solutions.

Management

Remotely access LoopEdge to reboot it or reset it to factory settings. Also, upload firmware upgrades to a device. Use DeviceHub to write values to a device. Use the LoopEdge Flows drag-and-drop, flow-based logic builder to write application logic for rules, alerts, and event processing.

LoopEdge Architecture

Industrial PC (IPC) Device: These devices, manufactured by major hardware vendors such as HP and Dell, have a customized operating system.&nbsp;

LoopEdge Software: Litmus Automation LoopEdge software installed on the IPC device, connects to devices (PLCs) and collects data from those devices. LoopEdge enables users to create custom flows of data from devices connected to custom applications. Flows are created via a browser-based drag-and-drop interface. The LoopEdge DataHub feature monitors the internet connection and preserves data locally, when a connection is dropped or not available. If a connection is dropped, the data is buffered and no data is ever lost. The DeviceHub component collects data from physical devices and publishes it to an internal message broker. The data is sent directly to the cloud via DataHub, or it is handled locally and sent to any desired destination, or both.

Flows: The LoopEdge Flows feature provides an easy drag-and-drop tool to connect hardware to the Internet, design APIs, and troubleshoot configurations.

Marketplace: Data processing applications are either developed by customers or downloaded from the marketplace of reusable components.

LoopCloud: LoopEdge can be configured to send data to Litmus Automation LoopCloud for device management and data visualization.

How do I access LoopEdge?

Prerequisite

An Internet browser that is connected to the same network as the LoopEdge device is required. Google Chrome, Mozilla Firefox, and Apple Safari are recommended.

Access LoopEdge software by connecting via a browser on the same network as the LoopEdge device. See the LoopEdge Network Diagram.

Enter the IP address into the browser URL, for example: 192.168.1.100

LoopEdge Network Diagram

Let's get started...

To explore LoopEdge features and benefits, read Why LoopEdge is a Whole OS and then start with the descriptions in LoopEdge Components Overview.