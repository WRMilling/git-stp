git-stp
---

git stash, test, pop.

### Installation

Run `sudo make install` to install to the default directory

### Configuration

You can create a `.test.cmd` file at the root of your git project tree which specifies the specific testing command, otherwise `rake` is assumed.

### Basic Usage

Run `git stp` to stash all uncommitted changes, test your code, and pop those changes

### Help Documentation
```
usage:
  git stp [options] [COMMAND] [args]

commands:
  git stp                         Stash all changes, test, and pop them back.

options:
  -h, --help                      Display this help information
  -v, --version                   Display this version of git-stp
```

### License

Please see the `LICENSE` file for full license.