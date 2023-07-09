# GitHub Viewer

A cli tool to explore public repositories hosted on GitHub.

## Prerequisites

Make sure you have the following dependencies installed in your environment:

- jq
- gh
- fzf
- bat

## Usage

Authenticate with github once using ```gh auth login```

```bash
./ghv nixos
./ghv nixos/nix
./ghv nixos/nix/README.md
./ghv https://github.com/nixos/nix/README.md
./ghv https://github.com/nixos/nix/blob/master/README.md
```

## LICENSE

Unlicense
