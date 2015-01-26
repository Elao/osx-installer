# Elao OSX Installer

Easily configure your osx installation with our standard stack

- Virtualbox
- Vagrant (with the landrush plugin)
- Zsh & Oh-My-Zsh
- Git
- Homebrew Cask

Plus, the wonderful...

- Ponysay

## Requirements

In order to run this script you need to install the osx command line tools,
homebrew and ansible

## Installation

```
wget -O installer.zip https://github.com/elao/osx-installer/archive/master.zip
unzip installer
cd installer
ansible-playbook -i hosts -K playbook.yml
```
