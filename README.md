# Duet

A code editor where one model writes code and another reviews it, in a loop, until the review approves.

## Install (Apple Silicon Macs)

```sh
brew install --cask harsha509/duet/duet
```

Update with `brew upgrade --cask duet`. Remove with `brew uninstall --cask duet`.

You can also download the DMG from [Releases](../../releases). Those builds are not notarized by Apple, so macOS will refuse to open the app until you allow it in **System Settings → Privacy & Security**. Installing with Homebrew avoids that step.

## Requirements

- macOS 12 or later, Apple Silicon
- An API key for Anthropic or Google Gemini (or an OpenAI-compatible endpoint), entered in Settings

This repository holds releases only.
