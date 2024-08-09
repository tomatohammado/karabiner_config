# Karabiner Configuration

This repo is to sync my Karabiner settings between macOS devices.

Used my fork of a `.keyboard` repo for a while ([Source](https://github.com/tomatohammado/keyboard)). I no longer use hammerspoon, and so I wanted a lighter repo just for Karabiner.

## Snippet: Symlinking the karabiner config

Adapted from the setup script from the old repo.

```sh
# Prepare custom settings for Karabiner-Elements
# https://github.com/tekezo/Karabiner-Elements/issues/597#issuecomment-282760186
mkdir -p ~/.config
ln -sfn $PWD/karabiner ~/.config/karabiner
```

## Instructions

1. Clone this repo on a new machine.

2. Run the snippet above. This will create a symlinked directory in the default locaton for Karabiner's config

3. Install Karabiner. I'd probably use homebrew.

4. Profit?
