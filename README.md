# Pulsar VPN - Release Binaries

This repository contains ONLY compiled release binaries and update
manifests for the Pulsar VPN Windows client. No source code.

## Channels (lowercase â€” GitHub raw URLs are case-sensitive)
- Windows/Installer/alpha/   - alpha channel installers
- Windows/Installer/beta/    - beta channel installers
- Windows/Installer/stable/  - stable channel installers

## Publish (never edit manifest.json by hand)
Run from client/windows/tools:
    .\publish_release.ps1 -File <path\to\exe> -Version 0.0.2 -Channel alpha

## Raw URLs
Manifest:
    https://raw.githubusercontent.com/xuanphantannguyet-source/pulsar-vpn-releases/main/Windows/Installer/<channel>/manifest.json
Installer:
    https://raw.githubusercontent.com/xuanphantannguyet-source/pulsar-vpn-releases/main/Windows/Installer/<channel>/<version>/<filename>
