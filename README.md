# Welcome to my Dots

### Dependencies
```bash
yay -S git neovim tmux zsh sway rofi 
```

### Tmux

#### Commands
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
#### To zshrc
```bash
export TERM="xterm-256color"
if [ -z "$TMUX" ]; then
    tmux attach -t default || tmux new -s default
fi
```
