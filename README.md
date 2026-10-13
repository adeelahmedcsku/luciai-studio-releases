# Luciai Studio — installers

The installers of **Luciai Studio**, the free, local-first AI IDE with the Lucicoder agent. This
repository holds the installers only; there is no source code here.

**Download:** from the website — <https://luciai.studio/download> — or from the
[latest release](../../releases/latest) on this page. No account is needed to download or to start.

## Which file

| System | File |
| --- | --- |
| Windows 10 / 11, 64-bit | `LuciaiStudio_<version>_x64-setup.exe` (recommended) or `LuciaiStudio_<version>_x64_en-US.msi` |
| macOS 11 or later, Apple silicon and Intel | `LuciaiStudio_<version>_universal.dmg` |
| Linux, 64-bit | `LuciaiStudio_<version>_amd64.AppImage` (any distribution), `LuciaiStudio_<version>_amd64.deb` (Ubuntu, Debian), `LuciaiStudio-<version>-1.x86_64.rpm` (Fedora, openSUSE) |

## Check a download

Every release has a `SHA256SUMS` file with the checksum of each installer.

- Windows (PowerShell): `Get-FileHash .\LuciaiStudio_2.8.0_x64-setup.exe -Algorithm SHA256`
- macOS (Terminal): `shasum -a 256 LuciaiStudio_2.8.0_universal.dmg`
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

## Free — no account to start

Luciai Studio is free, with no time limit.

1. **Install it and start it.** On its first start (online, once) your free month on this computer
   begins by itself — no account, no key.
2. **Before the month ends, create a free account** — in Luciai Studio, choose *Create a free account*.
   Confirm your email address, and your key with no time limit comes to the app by itself; nothing to
   paste.
3. On another computer, paste your key from your account at <https://luciai.studio/account>.

More: [your license, explained](https://luciai.studio/docs/license).

## Buy me a coffee

If Luciai Studio helps you, [buy me a coffee](https://buymeacoffee.com/adeelahmed2) and support
children in remote and poor areas of Pakistan in getting an education. *Every child deserves an
education. I will use this money to help poor and needy children in Pakistan get an education.*
Entirely up to you — Luciai Studio stays free either way.

Questions and problems: <https://luciai.studio/support>.
