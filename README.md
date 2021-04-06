# Spam
> a minimal package manager

Spam is a small work in progress package manager. It can only do the following:

* Install packages
* Remove packages
* Use repos
* Upgrade itself (WIP)

It **cannot**:
* Upgrade packages
* Setup itself for you


## Installation
```
sudo apt install git tar bash || sudo pacman -S git tar bash || sudo zypper in git tar bash || brew install git tar bash || sudo dnf install git tar bash || sudo emerge git tar bash || sudo xbps-install git tar bash || sudo pkg install git tar bash || sudo pkg_add git tar bash || sudo eopkg install git tar bash 
git clone https://github.com/bashelled/spam ~/.spam
mkdir -p ~/.spam/{pkg,usr/pkgcache}
echo "PATH=$HOME/.spam/bin:$PATH" >> ~/.*rc
```
