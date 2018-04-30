The **emend-computer** encapsulates app and bundles which represent
configuration items [emend](https://github.com/emend) processes.

## Prerequisites
1. Ruby
2. [emend](https://github.com/Traap/emend)

## Installation
### emend-computer 
```bash
$ cd $HOME
$ git clone http://github.com/Traap/emend-computer.git
```

### How to install an application. 
These examples install bash-git-prompt and colors applications to the speicic
operating sytesm [emend](https://github.com/emend) is run from.

```
cd emend-computer
emend --verbose --nodryrun --app=bash-git-prompt

emend --verbose --nodryrun --app=colors
```

### How to install a bundle. 
This example shows how to install the basic bundle. 

```bash
cd emend-computer
emend --verbose --nodryrun --bundle=basic

```
## Project Management
Please refer to my [Lightweight Project Management](https://github.com/Traap/lpm)
for the project management strategy I use.
