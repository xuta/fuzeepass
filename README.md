# fuzeepass

[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fxuta%2Ffuzeepass%2Fbadge%3Fref%3Dmain&style=flat)](https://actions-badge.atrox.dev/xuta/fuzeepass/goto?ref=main)
[![Coverage Status](https://coveralls.io/repos/github/xuta/fuzeepass/badge.svg?branch=main)](https://coveralls.io/github/xuta/fuzeepass?branch=main)
[![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://github.com/xuta/fuzeepass/blob/main/LICENSE)

A command-line fuzzy finder for KeePassX

## Features
![Animated demonstration](https://raw.githubusercontent.com/xuta/fuzeepass/main/assets/fuzeepass_1.gif)

* Fuzzy search powered by [fzf](https://github.com/junegunn/fzf)
* Convenient hot-keys
* Support update/create/delete new entries, groups
* Censored password by default
* Hot-key to copy password to clipboard

## Installation

* Requirements
    - [fzf](https://github.com/junegunn/fzf) >= 0.24.0, as a CLI interactive engine
    - [Linux] [xsel](https://github.com/kfish/xsel) or [xclip](https://github.com/astrand/xclip) to copy password to clipboard

```bash
# system wide
pip install fuzeepass

# or install to ~/.local/bin with
pip install --user fuzeepass
```

## Key-bindings

| Key                                             | Action                         |
| :---------------------------------------------: | ------------------------------ |
| <kbd>Ctrl</kbd> - <kbd>k</kbd>                  | Selection move up              |
| <kbd>Ctrl</kbd> - <kbd>j</kbd>                  | Selection move down            |
| <kbd>Ctrl</kbd> - <kbd>p</kbd>                  | Show password in preview panel |
| <kbd>Ctrl</kbd> - <kbd>y</kbd>                  | Copy password to clipboard     |
| <kbd>Ctrl</kbd> - <kbd>r</kbd> / <kdb>Esc</kbd> | Reload or back to main screen  |
| <kbd>Ctrl</kbd> - <kbd>c</kbd>                  | Switch to `Create` screen      |
| <kbd>Ctrl</kbd> - <kbd>u</kbd>                  | Switch to `Update` screen      |
| <kbd>Ctrl</kbd> - <kbd>d</kbd>                  | Switch to `Delete` screen      |
| <kbd>Ctrl</kbd> - <kbd>q</kbd>                  | Quit                           |

## How it works

**updating...**

## References
* Powered by [fzf](https://github.com/junegunn/fzf)
