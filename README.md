# GitHub Viewer

GitHub Viewer is a CLI tool built to explore public repositories hosted on GitHub. With GitHub Viewer, you can browse and view code hosted on GitHub repositories directly from your terminal using GitHub API.

## Prerequisites

Make sure you have the following dependencies installed in your environment:

- `jq`
- `gh`
- `fzf`
- `bat`
- `bash`

## Installation

For easier access, consider adding the `ghv` script to your `$PATH` so you can call it directly without specifying the script's location.

```
wget https://raw.githubusercontent.com/Creator54/ghv/main/ghv
chmod +x ghv
```

## Test

If you want to just test it out and have the dependencies installed you can use the following command:

```bash
curl -s https://raw.githubusercontent.com/Creator54/ghv/main/ghv | bash -s creator54/ghv
```

## Usage

Authenticate with github once using `gh auth login` to use the GitHub API

```bash
./ghv <username>
./ghv <username>/<repository>
./ghv <username>/<repository>/<path>
./ghv <repository-url>
./ghv <file-url>
```
[preview](https://github.com/Creator54/ghv/assets/34543609/891f98a2-692b-44df-9c7b-e50785c1996d)

## Current Limitations:

* shows only 100 repositories(max) present for the username
* files except text/markdown is not properly handled

## LICENSE

This project is licensed under the [Unlicense](./LICENSE).
