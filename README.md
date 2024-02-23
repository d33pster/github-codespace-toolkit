# <center>GitHub Codespace Toolkit </center>
<p><center>:made by d33pster:</center></p>
<p align='center'>
    <a href='#Installation'>Installation</a>
    &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href='#Usage'>Usage</a>
    &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href='#Uninstall'>Uninstall </a>
</p>

#### About
With Github Codespace, we can easily code amywhere and anytime. So why waste time on typing long git commands?

Github CodeSpace Toolkit is a lightweight easy to install toolkit to keep you coding without having to type long commands for git and other bash functionalities.

#### Installation
```console
# Run all the following commands in your github codespace terminal

## clone the repo
$ git clone https://github.com/d33pster/github-codespace-toolkit.git

## go inside the cloned directory
$ cd github-codespace-toolkit

## run setup
$ ./setup

### NOTE: Restart terminal
```

#### Usage
##### 1. Github CodeSpace Toolkit
###### (i) update command
update command can be used to easily push multiple files using one single command
```console
# update command
$ ./update -h
usage: 
    -h | --help    : Display this help module
    -m | --message : commit message (accepts string) (default - "udpate")
    -f | --files   : files (default - ALL)
```
###### (ii) pull command
```console
# pull command
$ ./pull
```
##### 2. Custombasher (Bonus)
Project Custombasher integrates sequences of commonly used bash commands into single small commands.
```console
# for custombasher help run
$ help
```
#### Uninstall
```console
# uninstall command
$ ./uninstall-github-codespace-toolkit
```