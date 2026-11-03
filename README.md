# Stackwarden

Stackwarden is a Mac app for administering Splunk Cloud Platform stacks through the Admin Config Service
(ACS): indexes, HEC tokens, IP allow lists, apps, users and roles, authentication tokens, maintenance and
change freezes, restarts, deployments and stack configuration, with Identity Management, Access Map,
Offboarding and Stack Compare included.

This repository holds the **releases** and **issue reports**. The source code is kept privately.

## Install

1. Download the latest `Stackwarden-<version>.dmg` from [Releases](../../releases/latest).
2. Open it and drag **Stackwarden** into **Applications**.
3. Open Stackwarden. It needs macOS 27 or later.

Every release is signed with a Developer ID and notarized by Apple. The `.sha256` file beside each disk
image holds its checksum.

## Updates

Stackwarden checks this repository for a new version once a day (Settings › General) or when you choose
**Stackwarden › Check for Updates…**. It installs an update only when you choose to, after checking the
download's checksum, its Developer ID signature and its notarization.

## Reporting a crash

If Stackwarden quits unexpectedly, the next launch offers **Report on GitHub…**, which opens a new issue
here, filled in with the crash summary. Read it, add what you were doing, and submit. Crash summaries hold
versions and code locations only, never stack names, tokens or data from your stacks.

For anything else, [open an issue](../../issues/new).

© 2026 Aaron Stone. All rights reserved.
