# bin

This is a collection of scripts that I use to automate my workflow. I wrote them to make my life easier, and I hope they can help you, too.

## Quick Start

Clone the repository:

```bash
git clone git@github.com:michen00/bin.git
```

Copy its contents to your `bin` directory:

```bash
cp -r ./bin/* ~/bin
```

Alternatively, you can create a symbolic link to the `bin` directory:

```bash
ln -s ./bin ~/bin
```

Add the `bin` directory to your `PATH`

```bash
export PATH="$HOME/bin:$PATH"
```

Add the above line to your favorite shell configuration file (e.g. `~/.bashrc`, `~/bash_profile`, etc.; it might already be there) and `source` it. For example, for zsh:

```bash
. ~/.zshrc
```

## Scripts

- `add-last-commit-hash`: Add the last commit hash to a given file (`.git-blame-ignore-revs` file by default).
- `chdirx`: Add `+x` permission to all executable files (that start with `#!`) in the given directory.
- `mergewith`: Merge the latest changes from a reference branch into the current branch (updating both).
- `touchx`: Create (or update) a file and add `+x` permission to it.
- `update-mine`: Update all branches with open pull requests authored by you.
