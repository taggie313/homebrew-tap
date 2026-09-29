# taggie313/homebrew-tap

Homebrew formulae and casks for [Elusive](https://elusive.net) tools.

```sh
brew tap taggie313/tap
brew install untofu
brew install --cask winbar
```

## untofu

Supplies missing fonts to any macOS app, on demand, instead of letting it
complain. Source: <https://github.com/taggie313/untofu>

```sh
brew install untofu
brew services start untofu
```

## winbar

A menu bar icon for a Windows 11 VM in [UTM](https://mac.getutm.app) on an Apple silicon Mac,
plus `winbar setup`, which tunes that VM to run quietly in the background, reached over Remote
Desktop in Windows App. Source: <https://github.com/taggie313/winbar>

```sh
brew install --cask winbar
```

Then open Winbar, and its **Set Up Winbar** window walks you through the rest. The cask installs
the same notarized disk image the release page offers.
