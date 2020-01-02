# Tmuxinator FZF Start

Uses fzf to provide a selection list for starting tmuxinator projects

## Overview:

tmuxinator-fzf-start.sh will open fzf with a multi select
list of tmuxinator projects.  Upon selecting project/s each
project will have `tmuxinator start` run, and when complete
tmux will be attached, or if tmux is already running, a
session selection interface will be provided.

If an initial query is provided, and only one match results,
the project will be automatically opened without user input.

## Usage

```bash
tmuxinator-fzf-start.sh
tmuxinator-fzf-start.sh "Query"
```

## Expectations

- tmuxinator is on $PATH
- fzf is on $PATH
- tmux is on $PATH

## Install

### Homebrew

```bash
brew tap camspiers/taps
brew install tmuxinator-fzf-start
```

### Manual

Download `tmuxinator-fzf-start.sh`, make it executable and ensure it is on your $PATH.
