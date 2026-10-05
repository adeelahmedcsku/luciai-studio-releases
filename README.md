# Luciai Studio — installers

The installers of **Luciai Studio**, the local-first AI IDE with the Lucicoder agent. This repository
holds the installers only; there is no source code here.

**Download:** from the website — <https://luciai-web.vercel.app/download> — or from the
[latest release](../../releases/latest) on this page.

## Which file

| System | File |
| --- | --- |
| Windows 10 / 11, 64-bit | `LuciaiStudio_<version>_x64-setup.exe` (recommended) or `LuciaiStudio_<version>_x64_en-US.msi` |
| macOS 11 or later, Apple silicon and Intel | `LuciaiStudio_<version>_universal.dmg` (since 2.6.0) |
| Linux, 64-bit | `LuciaiStudio_<version>_amd64.AppImage` (any distribution), `LuciaiStudio_<version>_amd64.deb` (Ubuntu, Debian), `LuciaiStudio-<version>-1.x86_64.rpm` (Fedora, openSUSE) |

## Check a download

Every release has a `SHA256SUMS` file with the checksum of each installer.

- Windows (PowerShell): `Get-FileHash .\LuciaiStudio_2.6.0_x64-setup.exe -Algorithm SHA256`
- macOS (Terminal): `shasum -a 256 LuciaiStudio_2.6.0_universal.dmg`
- Linux: `sha256sum -c SHA256SUMS --ignore-missing`

The value must be the one in `SHA256SUMS`.

## The first start

The installers are not code-signed yet.

- **Windows**: SmartScreen may say "Windows protected your PC" — choose **More info → Run anyway**.
- **macOS**: open the disk image and drag Luciai Studio to Applications. The app is not notarized by
  Apple: the first time, right-click (or Control-click) it in Applications and choose **Open**, then
  **Open** again — on macOS 15, System Settings → Privacy & Security → **Open Anyway**. After that it
  opens like any app.
- **Linux**: make the AppImage executable first (`chmod +x LuciaiStudio_*.AppImage`).

## Your license

Luciai Studio asks for a license key. Create a free account on the website and we email you your
key — Luciai Studio free for one month. **Professional**, paid once, keeps it working with no time
limit, with the same key. See [Pricing](https://luciai-web.vercel.app/pricing).

Questions and problems: <https://luciai-web.vercel.app/support>.
