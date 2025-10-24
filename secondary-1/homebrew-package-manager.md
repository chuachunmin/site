# Homebrew Package Manager

[Homebrew Page](https://brew.sh)

## Installation

1. Paste into Terminal and hit 'return' key:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2\. ![](<../.gitbook/assets/Screenshot 2022-03-16 at 1.00.24 PM.png>)

password doesn't show `***` or anything as preview. just type your mac user login password and hit the 'return' key on your keyboard.

3\. Once you see the prompt `(%)` it means that installation is completed, paste into Terminal the code below and hit 'return' key:

```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> .zprofile
```

4\. Quit and reopen Terminal. Type `brew`

## Usage

`brew update`: update homebrew & packages

`brew upgrade`: upgrade outdated packages

`brew list`: list packages installed via homebrew

`brew search package_name`: search for packages

`brew info package_name`: get info on package

`brew install package_name`: install package

`brew uninstall package_name`: uninstall package

`brew autoremove`: uninstall redundant dependency.

`brew cleanup`: removes all downloads more than 120 days old.
