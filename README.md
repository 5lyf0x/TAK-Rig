# TAK Rig

**TAK Rig** is an Android navigation and connectivity platform built for **off-roading, overlanding, remote travel, and multi-vehicle trips**.

It combines offline navigation with convoy awareness, local communications, shared trip data, recent satellite imagery, and tools designed for larger vehicle-mounted Android displays.

This repository contains compiled TAK Rig releases and release information only.

> **The TAK Rig application source code is not published in this repository.**

---

## Built for More Than Navigation

TAK Rig includes the usual off-road essentials—offline maps, routes, waypoints, track recording, and 3D terrain—but its main focus is helping you stay connected and informed when traveling with multiple vehicles or heading beyond reliable cell coverage.

### See Your Group on the Map

Compatible TAK Rig devices can share their locations so you can see where the rest of your group is while traveling.

Useful for:

- Multi-vehicle trail runs
- Overland convoys
- Keeping track of vehicles at intersections
- Regrouping when the convoy gets separated

### Stay Connected Off-Grid

TAK Rig can share information over supported local and mesh-style connections without relying entirely on the internet.

Depending on your setup, devices can share:

- Locations
- Waypoints
- Routes
- Map objects
- Trip information
- Messages

### Share Offline Data Between Vehicles

Prepared offline data can be transferred directly between compatible TAK Rig devices.

This can include:

- Offline maps
- Navigation data
- Elevation data
- Cell-coverage data
- Basemap information

That means one prepared vehicle can help get the rest of the group ready without everyone downloading the same data separately.

### Built-In Messaging & Voice

TAK Rig includes messaging and developing voice features for group travel.

The goal is to keep navigation, location sharing, and communication together in one system instead of jumping between several different apps.

### Designed for Vehicle Displays

TAK Rig is built around **larger landscape Android displays**, including compatible vehicle head units and tablets.

The full interface is available directly on the display, including:

- Mapping
- Navigation
- Route planning
- Communications
- Offline-data management
- 2D and 3D views

The current interface is intended for larger screens rather than compact handset layouts.

---

## Recent Satellite Imagery

TAK Rig can display recent **Sentinel-2 satellite imagery** directly on the map.

When internet access is available, you can look for newer imagery of the area you are exploring and keep downloaded imagery cached for later use.

Features include:

- Automatic imagery-date selection
- Manual date selection
- Cloud-cover filtering
- Local caching
- Imagery-date display

This can be useful for checking changing terrain, access roads, dry lake beds, burn areas, or other conditions that may not be reflected in older basemaps.

---

## Offline Navigation

TAK Rig supports offline routing so you can continue navigating when cellular coverage disappears.

Regional navigation packages can be downloaded ahead of time and stored on the device.

You can keep multiple regions installed and TAK Rig will use the appropriate data when planning a route.

---

## 3D Terrain

TAK Rig includes a full 3D terrain view to help you understand the landscape around a route.

You can:

- View terrain and elevation
- Follow your position in 3D
- Adjust pitch and viewing distance
- Change terrain exaggeration
- See routes and map objects in the terrain view

---

## More Than Just Map Data

TAK Rig can bring several useful information sources into the same map.

Current and developing integrations include:

- Weather
- Traffic
- Places search
- Satellite imagery
- Cellular coverage
- Aircraft information
- TAK-compatible data
- External sensors and plugins

This makes TAK Rig useful as a broader vehicle information platform, not just a trail map.

---

## TAK Compatibility

TAK Rig can also connect with supported TAK-compatible systems.

Advanced users can use this for additional servers, data sources, plugins, communications, and shared map information.

TAK connectivity is optional and is not required for normal off-road navigation.

---

## Core Off-Road Features

TAK Rig also includes the navigation tools you would expect from an off-road app:

- Offline maps
- Offline routing
- Route creation and editing
- Route recording
- Waypoints
- Shapes and geofences
- Imported map sources
- Terrain and elevation information
- 2D and 3D mapping
- GPS-centered navigation
- Route statistics

These provide the navigation foundation for TAK Rig's group, communications, and data-sharing features.

---

## Designed for Offline Use

TAK Rig is built around the idea that internet access may disappear during a trip.

Before leaving coverage, you can prepare:

- Offline maps
- Navigation data
- Elevation data
- Routes and waypoints
- Satellite imagery
- Regional datasets
- Trip-specific information

Once prepared, many of TAK Rig's core features can continue working without cellular service.

Live services such as weather, traffic, places search, or newly requested satellite imagery still require connectivity when refreshing data.

---

## Built for Multi-Vehicle Trips

TAK Rig is especially useful when several vehicles are traveling together.

Each vehicle can carry its own:

- Offline maps
- Navigation data
- Routes and trip information
- Position-sharing capability
- Messaging
- Local data-transfer capability

The goal is to help the group stay aware and connected as coverage comes and goes.

---

## Settings Backup & Restore

TAK Rig includes portable **Settings Backup & Restore**.

Backups preserve persistent user settings outside the TAK configuration tab, including supported service and API settings.

Large downloaded files are kept separate from settings backups, including:

- Offline map tiles
- Navigation packages
- Terrain data
- Cached satellite imagery

Backup files may contain service credentials and should be stored securely.

---

## Field Tested

TAK Rig is under active development and is tested during real-world vehicle and off-road use.

Field testing helps improve areas such as:

- GPS accuracy
- Route recording
- Offline navigation
- 3D terrain performance
- Large-screen usability
- Device-to-device communication
- Mesh connectivity
- Offline data handling
- Multi-vehicle workflows

---

## Planned Future Development

- XTAK VEIL node compatibility
- Bluetooth handset speaker/microphone compatibility

---

## Development Status

TAK Rig is **under active development**.

Current builds are functional and used in field testing, but features, interfaces, compatibility, and networking behavior may continue to change.

TAK Rig should currently be considered evolving enthusiast software rather than a finished commercial navigation product.

---

## User Guide

The current guide covers the main TAK Rig workflows, including offline preparation, maps and sources, navigation, route recording, 3D terrain, convoy features, Data Sync, Missions, dataset transfer, satellite imagery, communications, hardware/network options, and settings backup.

[**Download the TAK Rig v0.19.3 User Guide (PDF)**](./TAK-Rig-v0.19.3-User-Guide.pdf)

---

## Releases

Compiled APK files are available through the **GitHub Releases** section of this repository.

A release may include:

- `TAK Rig v<version>.apk`
- SHA-256 checksum
- Release notes
- Known issues or field-testing notes

The APK is the primary download.

---

## Installation

Download the latest APK from the **Releases** section and install it on a compatible Android tablet or vehicle-mounted Android system.

When updating TAK Rig, install the newer APK over the existing version.

Normal updates are intended to preserve your settings and application data.

---

## Verify a Download

Release APKs may include a SHA-256 checksum.

On Windows:

```powershell
Get-FileHash ".\TAK Rig v0.19.3.apk" -Algorithm SHA256
```

Compare the result with the SHA-256 value published with the release.

---

## Source Code

This repository is a **binary distribution repository**.

The TAK Rig application source code is private and is **not distributed through this repository**.

GitHub may automatically show **Source code (zip)** and **Source code (tar.gz)** links on Release pages. Those archives only contain files committed to this public release repository and **do not contain the TAK Rig application source code**.

---

## Disclaimer

TAK Rig is under active development.

Off-road and backcountry travel can involve changing trail conditions, closures, private property, weather, terrain hazards, inaccurate map data, GPS errors, mechanical problems, and areas without communications coverage.

Always use appropriate maps, judgment, vehicle preparation, recovery equipment, and backup navigation and communications methods.

TAK Rig should not be considered a substitute for certified navigation, emergency communication equipment, or other safety-critical systems.

---

**TAK Rig**

*Offline navigation, convoy awareness, field communications, and connected data for off-road and overland travel.*
