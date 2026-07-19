# jdm-deps

Pre-packaged third-party tool binaries for JDiskMark installers.

Release assets in this repo are downloaded at CI build time by the
[jdm-java](https://github.com/JDiskMark/jdm-java) build workflows and
bundled into installer packages.

## Contents

| Asset | Tag | Description |
|---|---|---|
| `smartctl-7.5-linux-x86_64.tar.gz` | `tools/smartctl-7.5` | `smartctl` binary from smartmontools 7.5 (Ubuntu 25.04 / amd64) |
| `smartctl-7.5-windows-x86_64.zip` | `tools/smartctl-7.5-win64` | `smartctl.exe` from smartmontools 7.5 (Windows 64-bit) |
| `smartctl-7.5-macos-arm64.tar.gz` | `tools/smartctl-7.5-macos-arm64` | `smartctl` binary from smartmontools 7.5 (macOS Apple Silicon) |
| `smartctl-7.5-macos-x86_64.tar.gz` | `tools/smartctl-7.5-macos-x86_64` | `smartctl` binary from smartmontools 7.5 (macOS Intel) |

## Updating a dependency

Run the appropriate workflow manually from the **Actions** tab.
Only org maintainers with write access can publish new releases.
