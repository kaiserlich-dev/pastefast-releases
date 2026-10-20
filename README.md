# Pastefast

Clipboard history on a shelf, searchable in a millisecond. For macOS 13 and later (Apple silicon and Intel), and for Linux with [Omarchy](https://omarchy.org) (x86_64).

**[Download the latest version](https://github.com/kaiserlich-dev/pastefast-releases/releases/latest)**: open the `.dmg` and drag Pastefast to Applications.

- ⇧⌘V opens the shelf over any app; ↩ pastes.
- Search everything you copied, text in screenshots included.
- Pinboards for what you keep; API keys and tokens are masked and forgotten after a day.
- Pastefast updates itself: new versions download in the background and install on a restart.

To paste for you, Pastefast asks for Accessibility permission the first time.

## Omarchy (Linux)

```sh
sudo pacman -S --needed wl-clipboard wtype
curl -fsSL https://github.com/kaiserlich-dev/pastefast-releases/releases/latest/download/install.sh | bash
```

Then press Super+Alt+V. The installer checks the download against the release's checksums, installs to `~/.local/opt/pastefast` and starts it; it follows your Omarchy theme and updates itself like the Mac app. Run the same command again to reinstall.

This repository holds the releases; each one is signed, notarized by Apple, and its checksums are signed with Pastefast's update key.
