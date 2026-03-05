# CentenV's `zsh` Config


## Installation

Clone this into a discrete directory and create a hardlink to it via the `ln` command.

```shell
git clone git@github.com:centenv-config/zshrcenten.git
ln <path-to-dir>/.zshrc ~/.zshrc
```

## Setup
This *zsh* setup is dependent on *oh-my-zsh* which can be installed with:

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```


## Plugins
zsh-autosuggestions: Used for inline command suggestions based on command history
```shell
git clone https://github.com/zsh-users/zsh-autosuggestions $HOME/.zsh/zsh-autosuggestions
```
zsh-autocompletion: Fish-like autocomplete menu
```shell
git clone --depth 1 https://github.com/marlonrichert/zsh-autocomplete.git $HOME/.zsh/zsh-autocompletion
```
