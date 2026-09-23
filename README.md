# Pulsar

A BepInEx mod manager and launcher for Valheim, Lethal Company, and more. Keep a profile for
each setup, install mods from Thunderstore, and switch between them in one click.

**Early release.** Expect rough edges, and please [report them](#reporting-a-bug).

## Download

Get the latest from **[Releases](https://github.com/SolrLabs/pulsar/releases/latest)**.

| System | File |
|---|---|
| Windows 10/11 (x64) | `Pulsar-win-Setup.exe` |
| Linux (x64) | `Pulsar.AppImage` |
| macOS (Apple Silicon) | `Pulsar-osx-Setup.pkg` |

Pulsar updates itself once installed. Download only from this page or
[pulsarmods.com](https://pulsarmods.com) — copies hosted anywhere else are not ours.

## Installing

Pulsar isn't code-signed yet, so Windows and macOS warn you the first time. That's expected, and
the steps below get past it. Code signing is planned.

### Windows

1. Run `Pulsar-win-Setup.exe`.
2. If you see **"Windows protected your PC"**, click **More info → Run anyway**.

Pulsar installs for your user only; no administrator rights are needed.

### Linux

1. Move `Pulsar.AppImage` somewhere you own, such as `~/Applications`.
2. Make it executable: `chmod +x ~/Applications/Pulsar.AppImage`
3. Run it.

Keep it in a folder you own. An AppImage in a system folder like `/opt` can't update itself.

### macOS

1. Open `Pulsar-osx-Setup.pkg`. macOS blocks it: **"Apple could not verify…"**. Click **Done**.
2. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to
   the message about `Pulsar-osx-Setup.pkg`.
3. Confirm with your password, then follow the installer.

## Reporting a bug

[Open a bug report](https://github.com/SolrLabs/pulsar/issues/new?template=bug_report.yml). If
Pulsar crashed, it offers to fill one in for you the next time it opens. Nothing is sent until you
submit it yourself.

Security problems: see [SECURITY.md](SECURITY.md).

## Privacy

This release has no accounts and no usage telemetry. It talks to Thunderstore to find and download
mods, and to this repository to check for updates. See
[pulsarmods.com/privacy](https://pulsarmods.com/privacy).

## License

Free to use, at your own risk. See [LICENSE](LICENSE).
