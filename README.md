# MCsync

A Minecraft launcher that keeps a group's modpacks in sync: install a pack once, and
every time you play it brings your mods and configs in line with the pack.

This repository only holds the downloads. Once installed, MCsync updates itself from
here.

## Download

Get the newest version from [Releases](https://github.com/zsigsza/MCsync-releases/releases/latest):

| System | Download |
| --- | --- |
| Windows | `MCsync_…_x64-setup.exe` |
| macOS (Intel and Apple silicon) | `MCsync_…_universal.dmg` |
| Linux | `MCsync_…_amd64.AppImage` |

On Linux, use the AppImage: it's the one that can update itself. Make it executable
(`chmod +x`) and run it.

## First start

MCsync isn't code-signed, so your system will warn you the first time:

- **Windows:** "Windows protected your PC". Click **More info**, then **Run anyway**.
- **macOS:** "can't be opened". Right-click the app, choose **Open**, then **Open** again.

## Running a server for your group

The `mcsync-server` downloads (one per system) keep a Minecraft server's mods and files in
step with a pack. See the release notes for how to set one up.
