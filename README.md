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

## Preview
https://github.com/Creator54/ghv/assets/34543609/296acf8d-5d1c-47b4-931e-bb29f38227a4

## Current Limitations:
* shows only 100 repositories(max) present for the username
* files except text/markdown is not properly handled

## LICENSE

Unlicense
