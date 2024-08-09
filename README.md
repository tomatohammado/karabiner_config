# Karabiner Configuration

This repository contains my Karabiner settings for synchronization across macOS devices.

## Background

Previously, I used a forked `.keyboard` repository that included Hammerspoon configurations ([Source](https://github.com/tomatohammado/keyboard)). As I no longer use Hammerspoon, this repository focuses solely on Karabiner for a more streamlined setup.

## Setup Instructions

1. Clone this repository on your new machine.

2. Create a symlink for the Karabiner configuration:

   ```sh
   mkdir -p ~/.config
   ln -sfn $PWD/karabiner ~/.config/karabiner
   ```

   - The symlink command creates a link between this repository and Karabiner's default configuration location.

3. Install Karabiner-Elements (recommended method: Homebrew)

   ```sh
   brew install --cask karabiner-elements
   ```

4. Open Karabiner-Elements. Your custom configurations should now be applied.
