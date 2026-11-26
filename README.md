# Native Battery Control

<div align="center">

**Take control of Android's native battery management.**

A lightweight, customizable, Shizuku-powered Android utility.

![Version](https://img.shields.io/badge/version-0.6.0-176B60?style=flat-square)
![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Shizuku](https://img.shields.io/badge/Powered_by-Shizuku-448AFF?style=flat-square)
![Root](https://img.shields.io/badge/Root-Not_required-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Public_Beta-orange?style=flat-square)

[![Download APK](https://img.shields.io/badge/Download_APK-v0.6.0-176B60?style=for-the-badge&logo=android&logoColor=white)](https://github.com/jared-dot/NativeBatteryControl-V2/releases/download/v0.6.0/NativeBatteryControl-v0.6.0.apk)

[Releases](../../releases) · [Report a Bug](../../issues/new) · [Request a Feature](../../issues/new)

</div>

---

## Overview

Native Battery Control provides direct access to Android's built-in battery management controls through a clean Material 3 interface.

Unlike traditional battery optimizers, it uses native Android commands through Shizuku instead of implementing a separate hibernation engine.

No root required. No unnecessary persistent optimization service.

## Features

### Native battery management

- Per-app Doze exemption management
- Standby bucket selection
  - Active
  - Working Set
  - Frequent
  - Rare
  - Restricted
- Background activity permissions
- Background execution permissions
- Manual force stop
- System app support

### Saved settings and enforcement

- Save preferred settings for individual apps
- Detect settings overridden by Android
- Manually reapply saved configurations
- Optional automatic reapplication
- Configurable reapplication intervals
- Prioritize persistent battery restrictions
- Skip recognized protected standby buckets

### Verification and diagnostics

- Immediate and delayed setting verification
- Successful and unsuccessful application feedback
- Widget protection detection
- Android policy warnings
- Copyable diagnostic logs

### Interface and customization

- Material 3 design
- Floating pill navigation
- Search and advanced filters
- Application icons and live status indicators
- Light, dark and system themes
- Custom accent colors
- Wallpaper-based dynamic colors
- Compact application cards

## Why Native Battery Control?

| Feature | Native Battery Control |
|---|---|
| Root required | No |
| Native Android battery controls | Yes |
| Custom hibernation engine | No |
| Per-app configuration | Yes |
| Automatic reapplication | Optional |
| Persistent optimization service | No |
| Adjustable appearance | Yes |

## Installation

1. Download the APK from the Releases page.
2. Install [Shizuku](https://shizuku.rikka.app/).
3. Start Shizuku using wireless debugging or ADB.
4. Install and open Native Battery Control.
5. Navigate to Settings and authorize Shizuku.
6. Select an application to manage its battery settings.

## How it works

Native Battery Control uses Android's native shell commands through Shizuku, including:

- `am set-standby-bucket`
- `cmd deviceidle whitelist`
- `cmd appops set`
- `am force-stop`

Settings are managed directly through Android rather than through a separate hibernation engine.

## Privacy

Application preferences and saved battery profiles are stored locally on the device.

The application is designed to operate without accounts, advertising, analytics or cloud-based battery management.

## Important information

Android may automatically override certain settings based on application usage, widgets, system exemptions or manufacturer-specific battery management policies.

Automatic reapplication is optional and does not permanently override Android's internal policies.

Restricting messaging applications, accessibility services, alarms or essential system applications may interfere with their functionality.

Use advanced restrictions responsibly.

## Compatibility

Currently in public beta.

Primarily tested on HONOR MagicOS. Compatibility with other Android devices and manufacturer-specific Android implementations may vary.

## Feedback and contributions

Bug reports, suggestions and compatibility reports are welcome.

When reporting an issue, please include:

- Device model
- Android version
- Native Battery Control version
- Description of the issue
- Diagnostic logs or screenshots, if available

## Disclaimer

This application is provided as-is. Users are responsible for changes made to their device's battery management settings.

---

<div align="center">

**Native Battery Control**

Built for users who want more control over Android.

If you find this project useful, consider giving it a star.

</div> 
