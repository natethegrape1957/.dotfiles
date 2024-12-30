# Dotfiles Info
## Requirements:
- Nerd font

### JetBrainsMono Nerd Font:
1. Install from https://www.nerdfonts.com/font-downloads
2. Move to `~/.fonts/`
3. Unzip the zip
4. Run the command `fc-cache -fv` to manually rebuild the font cash
**Reference:** [github.com](https://gist.github.com/matthewjberger/7dd7e079f282f8138a9dc3b045ebefa0)

### Operator Caska Nerd Font:
1. Use [github.com](https://github.com/Anant-mishra1729/Operator-caska-Font) to install.
2. After the fonts are moved into `~/.fonts/`, run the bash command `fc-cache -fv` to rebuilt the font cache.
3. Ensure that the `font-family` is set to `family=Operator-caska postscript_name=CaskaydiaCoveNF-Regular` in kitty.conf.

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

### Necessary programs:
- neovim
- hyprshot
- hyprpaper
- kitty
- mako
- wofi
- waybar

#### Install in one command
```bash
sudo pacman -S neovim hyprshot hyprpaper kitty mako waybar wofi
```
