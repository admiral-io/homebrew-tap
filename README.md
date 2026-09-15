> :warning: This project is currently **under heavy development and is not considered stable yet**. This means that there may be bugs or unexpected behavior, and we don't recommend using it in production.

# Homebrew Tap for Admiral

This is the official [Homebrew](https://brew.sh) tap for the [Admiral](https://admiral.io/) CLI.

## Available Formulae

| Formula   | Description                                  | License    |
| --------- | -------------------------------------------- | ---------- |
| `admiral` | Command-line client for the Admiral platform | Apache-2.0 |

## Installation

```sh
brew install admiral-io/tap/admiral
```

Or add the tap first, then install:

```sh
brew tap admiral-io/tap
brew install admiral
```

## Upgrading

```sh
brew update
brew upgrade admiral
```

## Uninstalling

```sh
brew uninstall admiral
```

To remove the tap as well:

```sh
brew untap admiral-io/tap
```

## Shell Completions

The `admiral` CLI ships with Bash, Zsh, and Fish completions, which Homebrew installs automatically.

## Supported Platforms

| OS    | Architecture          |
| ----- | --------------------- |
| macOS | Intel (x86_64)        |
| macOS | Apple Silicon (arm64) |
| Linux | x86_64                |
| Linux | arm64                 |

## Other Install Methods

- **Windows:** install via [Scoop](https://scoop.sh) from [admiral-io/scoop-bucket](https://github.com/admiral-io/scoop-bucket).
- **Linux packages, Docker, and standalone binaries:** see the [admiral-cli releases](https://github.com/admiral-io/admiral-cli/releases).

The Admiral server is not distributed through this tap.

## License

This tap's metadata is licensed under Apache-2.0. See [LICENSE](LICENSE) for details. The `admiral` formula installs software under its own upstream license (see the table above).
