# Dev-Toolbelt/homebrew-devteam

Homebrew tap for [dev-team-agents](https://github.com/Dev-Toolbelt/dev-team-agents).

## Install

```bash
brew install dev-toolbelt/devteam/devteam
```

That installs the `devteam` CLI and the Python it runs on. Then put the framework in the store
and bind a project:

```bash
devteam update
devteam bind /path/to/project
```

## What lives here

| Formula | Installs |
|---------|----------|
| `devteam` | The `devteam` CLI — the global store manager of dev-team-agents |

## Where the formula comes from

The source of truth is [`packaging/homebrew/devteam.rb`](https://github.com/Dev-Toolbelt/dev-team-agents/blob/main/packaging/homebrew/devteam.rb)
in the main repository. Its release workflow rewrites the `url` and `sha256` for each `vX.Y.Z`
tag; the result is copied here. Do not edit the formula in this repository — change it there.

Without Homebrew, install the CLI with
[`scripts/install-cli.sh`](https://github.com/Dev-Toolbelt/dev-team-agents/blob/main/scripts/install-cli.sh).

## License

MIT
