# my-kitty-setup

My [kitty](https://sw.kovidgoyal.net/kitty/) terminal setup: Catppuccin Mocha colours, JetBrainsMono Nerd Font, gnome-terminal-style keybindings, and a [Starship](https://starship.rs) prompt that shows the git branch and status and starts the path at the repo root inside a git repo or worktree.

## Install

Requires the JetBrainsMono Nerd Font.

```sh
git clone https://github.com/Najidnadri/my-kitty-setup.git ~/.config/kitty

# Prompt
curl -sS https://starship.rs/install.sh | sh
ln -s ~/.config/kitty/starship.toml ~/.config/starship.toml
echo 'eval "$(starship init bash)"' >> ~/.bashrc
```
