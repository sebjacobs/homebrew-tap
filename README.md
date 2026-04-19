# homebrew-tap

Personal [Homebrew](https://brew.sh) tap for [@sebjacobs](https://github.com/sebjacobs)' tools.

## Usage

```bash
brew tap sebjacobs/tap
brew install <name>
```

Or install directly without tapping first:

```bash
brew install sebjacobs/tap/<name>
```

## Packages

| Name | Description | Source |
| --- | --- | --- |
| `jotter` | Append-only session log tool for Claude Code | [sebjacobs/jotter](https://github.com/sebjacobs/jotter) |

## How packages get here

Each source project uses [GoReleaser](https://goreleaser.com) to publish its cask to this repo automatically on every release tag. Don't edit `Casks/*.rb` by hand — changes will be overwritten on the next release.

These are Homebrew **casks**, not formulae, because they install pre-compiled binaries rather than building from source — which matches [Homebrew's own definition](https://docs.brew.sh/Formula-Cookbook#homebrew-terminology) of the two package types.
