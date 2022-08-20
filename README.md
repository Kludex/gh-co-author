# GitHub Co-author Extension

This is a GitHub CLI extension that generates `Co-authored-by` to be added as a *trailer*
to the commit message.

This repository is just a wrap around what [Hynek Schlawack](https://github.com/hynek) did on
their article [TIL: Easier Crediting of Contributors on GitHub](https://hynek.me/til/easier-crediting-contributors-github/).

## Installation

You need to have [GitHub CLI](https://cli.github.com/) installed, and then:

```bash
gh extension install Kludex/gh-co-author
```

## Usage

There's a single command available:

```bash
gh co-author AUTHOR
```
