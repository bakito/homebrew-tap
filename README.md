# bakito/homebrew-tap

A small Homebrew tap for distributing macOS applications as Homebrew Casks.  
This tap contains only Casks (no Formulae). Replace example names below with the actual cask names in this repository.

## Quickstart

Tap this repository:

```bash
rew tap bakito/home
```

Install a cask from this tap:

```bash
# Fully qualified
brew install --cask bakito/homebrew-tap/myapp

# Or, after tapping, if the name does not conflict:
brew install --cask myapp
```

Upgrade installed casks:

```bash
brew update
brew upgrade --cask myapp
```

Uninstall:

```bash
brew uninstall --cask myapp
```
