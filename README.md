# CentenV's `zsh` Config


## Installation

Clone this into a discrete directory and create a hardlink to it via the `ln` command.

```shell
git clone git@github.com:centenv-config/zshrcenten.git
ln <path-to-dir>/.zshrc ~/.zshrc
```

## Setup
This *zsh* setup is dependent on *oh-my-zsh* which can be installed with:

```sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```


## Plugins
zsh-autosuggestions: Used for inline command suggestions based on command history
```git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions```
