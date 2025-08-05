# LazyOC Homebrew Tap

This is the Homebrew tap for [LazyOC](https://github.com/katyella/lazyoc), a lazy terminal UI for OpenShift/Kubernetes clusters.

## Installation

```bash
brew tap katyella/tap
brew install lazyoc
```

## Updating

```bash
brew update
brew upgrade lazyoc
```

## Manual Installation

If you prefer not to use the tap:

```bash
# Download latest release
curl -L https://github.com/katyella/lazyoc/releases/latest/download/lazyoc_$(uname -s)_$(uname -m).tar.gz | tar xz
sudo mv lazyoc /usr/local/bin/
```
