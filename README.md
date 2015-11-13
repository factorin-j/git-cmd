# Custom Git Commands
Custom git commands that can be useful if you are using git cli

## Installation

```bash
$ curl -s -L https://github.com/jm-factorin/git-cmd/raw/master/git-compare > git-compare
$ chmod +x git-compare
$ sudo mv git-compare /usr/local/bin/
```

## Usage

```bash
# Using default (current) branch
$ git compare #https://github.com/jm-factorin/git-cmd/compare/dev
```

```bash
# Using base branch
$ git compare master #https://github.com/jm-factorin/git-cmd/compare/master...dev
```

```bash
# Using base and compare branches
$ git compare base-master dev-new-branch #https://github.com/jm-factorin/git-cmd/compare/base-master...dev-new-branch
```
