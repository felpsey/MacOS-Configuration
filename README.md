## Steps to bootstrap a new Mac

1. Install Apple's Command Line Tools, which are prerequisites for Git and Homebrew.

```zsh
xcode-select --install
```


2. Clone repo into new hidden directory.

```zsh
git clone git@github.com:felpsey/dotfiles.git ~/.dotfiles
```


3. Run the install script

```zsh
cd ~/MacOS-Configuration && sh install.sh
```
