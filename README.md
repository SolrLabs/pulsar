# Pulsar

A profile for every world.

Pulsar is a mod manager and launcher for BepInEx games like Valheim and Lethal Company. Create
as many profiles as you want per game, install your mods from Thunderstore, and switch between
them in one click.

**Early release.** Expect rough edges, and please [report them](#help-and-bug-reports).

## Download

Each link downloads the latest version for that system.

| System | Download |
|---|---|
| Windows 10 or later (x64) | [Pulsar-win-Setup.exe](https://github.com/SolrLabs/pulsar/releases/latest/download/Pulsar-win-Setup.exe) |
| Linux (x64) | [Pulsar.AppImage](https://github.com/SolrLabs/pulsar/releases/latest/download/Pulsar.AppImage) |
| macOS 12 or later (Apple Silicon) | [Pulsar-osx-Setup.pkg](https://github.com/SolrLabs/pulsar/releases/latest/download/Pulsar-osx-Setup.pkg) |
| macOS 12 or later (Intel) | [Pulsar-osx-x64-Setup.pkg](https://github.com/SolrLabs/pulsar/releases/latest/download/Pulsar-osx-x64-Setup.pkg) |

Older versions and changelogs are on the [Releases](https://github.com/SolrLabs/pulsar/releases) page.

Once it's installed, Pulsar updates itself. Only download it from this page or
[pulsarmods.com](https://pulsarmods.com/github). Copies anywhere else aren't ours.

## Installing

The Windows and macOS installers are signed by SolrLabs LLC. Windows may ask you to confirm the
first time you open it, and the steps below walk you through it.

### Windows

1. Run `Pulsar-win-Setup.exe`.
2. If you see **"Windows protected your PC"**, choose **More info**. It names SolrLabs LLC as the
   publisher. Then choose **Run anyway**.

Pulsar installs for your user only, so you don't need administrator rights.

### Linux

1. Move `Pulsar.AppImage` somewhere you own, like `~/Applications`.
2. Make it executable: `chmod +x ~/Applications/Pulsar.AppImage`
3. Run it.

Keep it in a folder you own. An AppImage in a system folder like `/opt` can't update itself.

### macOS

1. Open `Pulsar-osx-Setup.pkg` (or `Pulsar-osx-x64-Setup.pkg` on an Intel Mac).
2. Follow the installer, and enter your password when it asks.

## Help and bug reports

[Join us on Discord](https://discord.gg/69EDBhux78) to ask a question, report a bug or suggest an
idea. If Pulsar crashes, it offers to fill in a bug report for you the next time you open it.
Nothing is sent until you submit it yourself.

For security problems, see [SECURITY.md](SECURITY.md).

## Privacy

Pulsar has no accounts. It can send anonymous usage statistics and crash reports, which you can
turn off in Settings. It also talks to Thunderstore to find and download mods, and to this
repository to check for updates. The details are at
[pulsarmods.com/privacy](https://pulsarmods.com/privacy).

## How it's made

Pulsar is built by a solo developer with 25 years of development experience using AI-assisted
coding tools. Every release runs about 3,500 automated tests on Mac, Windows and Linux before it
ships, and it's tested by hand on all three. Issues are actively monitored for bugs, and new
features are planned for near-term release.

## License

Free to use, at your own risk. See [LICENSE](LICENSE).
