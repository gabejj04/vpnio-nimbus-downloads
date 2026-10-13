# VPNIO Nimbus download mirror

Permanent download: https://github.com/gabejj04/vpnio-nimbus-downloads/releases/latest/download/nimbus.apk

Original project: https://github.com/wilson1442/nimbus-speedtest

This repository distributes an unchanged APK; it does not claim authorship of Nimbus. Current mirrored release: 1.7.4 / build 16, Android 7.0+, 8,491,168 bytes.

SHA-256: `2e30c8aa763bc544b95745b5f3f0d94c725a26093bd959e34cd53aea827b48ad`

The app's built-in updater still contacts the original repository. This mirror does not automatically track upstream releases.

## Publish a future mirror

1. Review the original release and confirm redistribution permission.
2. Download the signed upstream APK and verify package identity, version, signer continuity and published checksum.
3. Create a new GitHub release here with the upstream version tag and attribution. Upload the unchanged APK named exactly `nimbus.apk` and mark the release as Latest.
4. Download through the permanent link and confirm the checksum matches.
5. Update the VPNIO Nimbus page's version, size and checksum to match.

## Static review

Download/upload bandwidth, HTTP latency and jitter, failed-HTTP-probe percentage, app-calculated quality score, local history, selectable LibreSpeed-compatible servers, touch/TV D-pad controls and consent-based updates are present in the reviewed source and APK metadata/DEX evidence.

The manifest requests internet, network/Wi-Fi state, installation of update packages and an app-scoped receiver permission. The APK contains the public-IP lookup endpoint api.ipify.org and the original GitHub update endpoint. This was static inspection, not a device execution test or full security audit.
