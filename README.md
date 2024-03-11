# Setup

## Install

- zsh <(curl -s https://raw.githubusercontent.com/zap-zsh/zap/master/install.zsh) --branch release-v1 

- curl -sS https://starship.rs/install.sh | sh

## Link files

- link dotZshrc to ~/.zshrc
- link dotXmodmap to ~/.Xmodmap

## Remap Space and Esc

- add the following to your x startup
```
xcape -e 'Caps_Lock=Escape;Shift_R=space'
```
