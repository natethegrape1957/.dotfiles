# Dotfiles Info
## Requirements:
- Nerd font

## JetBrainsMono Nerd Font:
1. Install from https://www.nerdfonts.com/font-downloads
2. Move to `~/.fonts/`
3. Unzip the zip
4. Run the command `fc-cache -fv` to manually rebuild the font cash
5. asdfasdf
**Reference:** [github.com](https://gist.github.com/matthewjberger/7dd7e079f282f8138a9dc3b045ebefa0)

## Installation:
- Load nvim submodule
```bash
git submodule update --init
```

- Initialize Symlinks 
```bash
~/.dotfiles/initsymlink.sh
```

- Starship:
```bash
curl -sS https://starship.rs/install.sh | sh

# ~/.bashrc
eval "$(starship init bash)"
```

- Install Curl:
```bash
sudo apt install curl

- Install Homebrew:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Install nvim
```bash
brew install neovim
```

## Changes to dotfiles:
### starship.toml:
```toml
[░▒▓](#a3aed2)\
```
This was removed.

```toml
[  ](bg:#a3aed2 fg:#090c0c)\
```

Apple logo replaced with Ubuntu logo.
