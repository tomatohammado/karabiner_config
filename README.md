# Karabiner Configuration

This repository contains my Karabiner settings for synchronization across macOS devices.

## Background

Previously, I used a forked `.keyboard` repository that included Hammerspoon configurations ([Source](https://github.com/tomatohammado/keyboard)). As I no longer use Hammerspoon, this repository focuses solely on Karabiner for a more streamlined setup.

## Setup Instructions

1. Clone this repository on your new machine. `cd` into the local repo.

2. Create a symlink for the Karabiner configuration:

   ```sh
   # Prepare custom settings for Karabiner-Elements
   # https://github.com/tekezo/Karabiner-Elements/issues/597#issuecomment-282760186
   mkdir -p ~/.config
   ln -sfn $PWD/karabiner ~/.config/karabiner

   # Confirm
   ls -l ~/.config/karabiner
   ```

   - The symlink command creates a link between this repository and Karabiner's default configuration location.

3. Install Karabiner-Elements (recommended method: Homebrew)

   ```sh
   brew install --cask karabiner-elements
   ```

4. Open Karabiner-Elements. Your custom configurations should now be applied.

## Useful Links

- [StackOverflow about ln command flags](https://superuser.com/a/938865)
- [Github issue in Karabiner repo by author about the symlinking solution](https://github.com/tekezo/Karabiner-Elements/issues/597#issuecomment-282760186)

---

- [Old Medium article where I probably found the repo I forked](https://medium.com/@caulfieldOwen/turn-your-keyboard-into-a-text-editing-rocket-1514d8474d2d)
