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

## Current Casks

The following casks are present in this tap (results may be incomplete — check the Casks directory for more):

- kubexporter — Export Kubernetes resources for backup and migration.
  - Upstream/homepage: https://github.com/bakito/kubexporter

For the full list of casks in this repository, view the Casks directory on GitHub:
https://github.com/bakito/homebrew-tap/tree/main/0.8.2
