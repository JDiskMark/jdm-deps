# jdm-deps

Pre-packaged third-party tool binaries for JDiskMark installers.

Release assets in this repo are downloaded at CI build time by the
[jdm-java](https://github.com/JDiskMark/jdm-java) build workflows and
bundled into installer packages.

## Contents

| Asset | Tag | Description |
|---|---|---|
| `smartctl-7.5-linux-x86_64.tar.gz` | `tools/smartctl-7.5` | `smartctl` binary from smartmontools 7.5 (Ubuntu 25.04 / amd64) |

## Updating a dependency

Run the appropriate workflow manually from the **Actions** tab.
Only org maintainers with write access can publish new releases.
