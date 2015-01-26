# Elao OSX Installer

Easily configure your osx installation with our standard stack

- Virtualbox
- Vagrant (with the landrush plugin)
- Zsh & Oh-My-Zsh
- Git
- Homebrew Cask
- Atom Editor
- Php 5.6
- Adium

Plus, the wonderful...

- Ponysay

## Requirements

In order to run this script you need to install the osx command line tools,
homebrew, ansible and wget.

## Installation

```
wget -O installer.zip https://github.com/emerick42/osx-installer/archive/master.zip
unzip installer
cd installer
ansible-playbook -i hosts -K playbook.yml
```
