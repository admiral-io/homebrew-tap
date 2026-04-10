> :warning: This project is currently **under heavy development and is not considered stable yet**. This means that there may be bugs or unexpected behavior, and we don't recommend using it in production.

# Homebrew Tap for Admiral

This is the official [Homebrew](https://brew.sh) tap for [Admiral](https://admiral.io/) tools.

## Available Formulae

| Formula          | Description                                       | License       |
| ---------------- | ------------------------------------------------- | ------------- |
| `admiral`        | Command-line client for the Admiral platform      | Apache-2.0    |
| `admiral-server` | Admiral platform orchestrator (server and web UI) | AGPL-3.0-only |

## Installation

First, add the tap:

```sh
brew tap admiral-io/tap
```

Then install the formula(e) you need:

```sh
# CLI
brew install admiral

# Server (web + API)
brew install admiral-server
```

You can also install in a single command without tapping first:

```sh
brew install admiral-io/tap/admiral
brew install admiral-io/tap/admiral-server
```

## Upgrading

```sh
brew update
brew upgrade admiral admiral-server
```

## Uninstalling

```sh
brew uninstall admiral
brew uninstall admiral-server
```

## Shell Completions

The `admiral` CLI ships with Bash, Zsh, and Fish completions, which Homebrew installs automatically.

## Supported Platforms

| OS    | Architecture          | `admiral` | `admiral-server` |
| ----- | --------------------- | :-------: | :--------------: |
| macOS | Intel (x86_64)        |    ✓      |        ✓         |
| macOS | Apple Silicon (arm64) |    ✓      |        ✓         |
| Linux | x86_64                |    ✓      |        ✓         |
| Linux | arm64                 |    ✓      |        ✓         |

## Windows

Windows users can install the `admiral` CLI via [Scoop](https://scoop.sh) from our bucket at [admiral-io/scoop-bucket](https://github.com/admiral-io/scoop-bucket). Scoop is not covered by this tap. `admiral-server` is not distributed for Windows.

## License

This tap's metadata is licensed under Apache-2.0. See [LICENSE](LICENSE) for details. Each installed formula carries its own upstream license (see the table above).
