# Welcome to my Dots

### Tmux

#### Commands
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
#### To zshrc
```bash
if [ -z "$TMUX" ]; then
    tmux attach -t default || tmux new -s default
fi
```
