# Dotfiles

Dotfiles managed by [chezmoi](https://github.com/twpayne/chezmoi).

**Bootstrap**

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install chezmoi
chezmoi init xorima
```

**work**

```bash
brew install lastpass-cli
lpass login <email>
```

repo is cloned to `~/.local/share/chezmoi`
