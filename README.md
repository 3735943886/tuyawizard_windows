# tuyawizard for Windows

> **This repository has been merged into the main [tuyawizard](https://github.com/3735943886/tuyawizard) repo and is now archived.**
> The Windows `.exe` is built directly from the main repo as of v0.1.7 and is attached to each release. Download the latest from the [tuyawizard releases page](https://github.com/3735943886/tuyawizard/releases/latest).

---

Single-file Windows `.exe` build of [tuyawizard](https://github.com/3735943886/tuyawizard) — an interactive CLI for discovering and managing devices on the Tuya Cloud via QR-code login.

## Download

Grab the latest zip from the [Releases](https://github.com/3735943886/tuyawizard_windows/releases) page, unzip it, and run `tuyawizard.exe`.

## Usage

Double-click `tuyawizard.exe` to run with `--postprocess` enabled by default.

For other options, run it from `cmd` or PowerShell:

```
tuyawizard.exe --postprocess-only
tuyawizard.exe -device-file mydevices.json --postprocess
tuyawizard.exe --postprocess-mode scan
```

See the [upstream tuyawizard project](https://github.com/3735943886/tuyawizard) for full CLI options and Python library usage.

## Build

Builds are produced by [GitHub Actions](.github/workflows/build.yml) using PyInstaller on `windows-latest`. Push a `v*` tag to publish a new release.
