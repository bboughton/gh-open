# gh-open

A command-line utility to quickly open GitHub URLs in your browser from any
location within a Git repository.

## Overview

`gh-open` is a GitHub cli (`gh`) extension that intelligently opens GitHub URLs
based on your current context and input. It supports opening directories,
files, specific commits, and even specific lines within files directly in your
browser.

## Installation

```
gh extension install bboughton/gh-open
```

## Usage

```bash
# Open current directory in GitHub
gh-open

# Open a specific file
gh-open src/main.js

# Open a file at a specific line
gh-open src/main.js:42

# Open a specific commit
gh-open abc1234

# Open a file at a specific commit
gh-open abc1234:src/main.js

# Open a file at a specific line within a commit
gh-open abc1234:src/main.js:42
```
