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
./ghv creator54
./ghv creator54/ghv
./ghv creator54/ghv/README.md
./ghv https://github.com/creator54/ghv/README.md
./ghv https://github.com/creator54/ghv/blob/main/README.md
```

## LICENSE

Unlicense
