The **emend-computer** encapsulates app and bundles which represent
configuration items [emend](https://github.com/emend) processes.

# Prerequisites
1. Ruby
2. [emend](https://github.com/emend)

# Installation
## emend-computer 
```bash
$ cd $HOME
$ git clone http://github.com/Traap/emend-computer.git
```

## How to install an application. 
These example installs the gcc and Haskell compile specific to the operations
system [emend](https://github.com/emend) is run from.

```
cd emend-computer
emend --verbose --nodryrun --app=gcc

emend --verbose --nodryrun --app=haskell
```

## Custom installations:
This example shows how to install TMUX.

```bash
cd emend-computer
emend --verbose --nodryrun --file=apps/tmux/tmux.yaml

```
# Project Management
Please refer to my [Lightweight Project Management](https://github.com/Traap/lpm)
for the project management strategy I use.
