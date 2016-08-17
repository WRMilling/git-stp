# git-stp

git stash, test, pop.

### Installation

Run `sudo make install` which will install the git-stp file to the /usr/local/bin directory.

If you would rather install it yourself just move the git-stp file into a direcory on your `$PATH` and make sure it is executable. 

### Configuration

You can create a `.test.cmd` file at the root of your git project tree which specifies the testing command for your project, otherwise `rake` is assumed.

### Basic Usage

Run `git stp` to stash all uncommitted changes, test your code, and pop those changes.

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

The MIT License (MIT) Copyright (c) 2016 Winston R. Milling

Please see the `LICENSE` file for full text.
