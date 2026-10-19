# dotfiles

Personal configuration files.

| File | Purpose |
|---|---|
| `.editorconfig` | Indentation and charset settings for editors |
| `.gitconfig` | Git aliases and defaults |
| `.gitattributes` | Line ending normalization |

## Install

```bash
git clone https://github.com/Mister-Robot-Cat/dotfiles.git ~/dotfiles
cp ~/dotfiles/.editorconfig ~/
git config --global include.path ~/dotfiles/.gitconfig
```
