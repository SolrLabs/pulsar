# Pulsar

A profile for every world.

Pulsar is a mod manager and launcher for BepInEx games like Valheim and Lethal Company. Create
as many profiles as you want per game, install your mods from Thunderstore, and switch between
them in one click.

**Early release.** Expect rough edges, and please [report them](#reporting-a-bug).

## Download

Each link downloads the latest version for that system.

| System | Download |
|---|---|
| Windows 10 or later (x64) | [Pulsar-win-Setup.exe](https://github.com/SolrLabs/pulsar/releases/latest/download/Pulsar-win-Setup.exe) |
| Linux (x64) | [Pulsar.AppImage](https://github.com/SolrLabs/pulsar/releases/latest/download/Pulsar.AppImage) |
| macOS 12 or later (Apple Silicon) | [Pulsar-osx-Setup.pkg](https://github.com/SolrLabs/pulsar/releases/latest/download/Pulsar-osx-Setup.pkg) |

Older versions and changelogs are on the [Releases](https://github.com/SolrLabs/pulsar/releases) page.

Once it's installed, Pulsar updates itself. Only download it from this page or
[pulsarmods.com](https://pulsarmods.com). Copies anywhere else aren't ours.

## Installing

Pulsar isn't code-signed yet, so Windows and macOS ask you to confirm the first time you open it.
The steps below walk you through it.

### Windows

1. Run `Pulsar-win-Setup.exe`.
2. If you see **"Windows protected your PC"**, choose **More info**, then **Run anyway**.

Pulsar installs for your user only, so you don't need administrator rights.

### Linux

1. Move `Pulsar.AppImage` somewhere you own, like `~/Applications`.
2. Make it executable: `chmod +x ~/Applications/Pulsar.AppImage`
3. Run it.

Keep it in a folder you own. An AppImage in a system folder like `/opt` can't update itself.

### macOS

1. Open `Pulsar-osx-Setup.pkg`. macOS blocks it with **"Apple could not verify…"**. Click
   **Done**.
2. Go to **System Settings**, then **Privacy & Security**. Scroll down and click **Open Anyway**
   next to the message about `Pulsar-osx-Setup.pkg`.
3. Enter your password, then follow the installer.

## Reporting a bug

[Open a bug report](https://github.com/SolrLabs/pulsar/issues/new?template=bug_report.yml). If
Pulsar crashes, it offers to fill one in for you the next time you open it. Nothing is sent until
you submit it yourself.

For security problems, see [SECURITY.md](SECURITY.md).

## Privacy

This release has no accounts and no usage telemetry. It talks to Thunderstore to find and download
mods, and to this repository to check for updates. The details are at
[pulsarmods.com/privacy](https://pulsarmods.com/privacy).

## License

Free to use, at your own risk. See [LICENSE](LICENSE).
