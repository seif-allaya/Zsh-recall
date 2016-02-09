<p align="center">
Zsh-recall is a lightweight version of the Oh-My-Zsh project that aims to bundle the minimal required installation and it's tuned with my preferences. Yeah am too lazy :p
</p>

We higly recommend you to learn more about the original Oh-My-Zsh project through the official website [ohmyz.sh](http://ohmyz.sh).

## Getting Started

### Prerequisites

* `curl` or `wget` should be installed
* `git` should be installed

### Basic Installation

Zsh-recall is installed by running one of the following commands in your terminal. You can install this via the command-line with either `curl` or `wget`.

```shell
sh -c "$(curl -fsSL https://raw.github.com/darks/oh-my-zsh/master/tools/install.sh)"
```
OR

```shell
sh -c "$(wget https://raw.github.com/darks/oh-my-zsh/master/tools/install.sh -O -)"
```

## Using Oh My Zsh

### Plugins

Oh My Zsh comes with a shit load of plugins. But as Zsh-recall is a lightweight version, I have removed the majority of the plugins that I don't use. The few left can be found under the /Plugins directory.
#### Enabling Plugins

To enable a plugin you will need to edit the `~/.zshrc` file.

```shell
plugins=(git gem ruby)
```

### Themes

Same for the Plugins the few themes availables are located under the /themes directory. Again of this lack of choice matter you check out the Oh My Zsh project ;)  

#### Selecting a Theme

Oh-My-Zsh said : _Robby's theme is the default one. It's not the fanciest one. It's not the simplest one. It's just right (for him)._
Zsh-recall reply: _Okay, the Darks theme is gonna be the right one now_

To change the theme you will need to edit the `~/.zshrc` file.

```shell
ZSH_THEME="darks"
```

Also there is an option that allow random theming.

```shell
ZSH_THEME="random" # (...please let it be pie... please be some pie..)
```

#### Manual Installation

##### 1. Clone the repository:

```shell
git clone git://github.com/darks/oh-my-zsh.git ~/.zsh-recall
```

##### 2. *Optionally*, backup your existing `~/.zshrc` file:

```shell
cp ~/.zshrc ~/.zshrc.orig
```

##### 3. Create a new zsh configuration file

You can create a new zsh config file by copying the template that we included for you.

```shell
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```

##### 4. Change your default shell

```shell
chsh -s /bin/zsh
```

##### 5. Initialize your new zsh configuration

Once you open up a new terminal window, it should load zsh with the new configuration.


### Custom Plugins and Themes

If you want to override any of the default behaviors, just add a new file (ending in `.zsh`) in the `custom/` directory.

If you have many functions that go well together, you can put them as a `XYZ.plugin.zsh` file in the `custom/plugins/` directory and then enable this plugin.

If you would like to override the functionality of a plugin distributed with Oh My Zsh, create a plugin of the same name in the `custom/plugins/` directory and it will be loaded instead of the one in `plugins/`.

## Getting Updates

No updates Here, Yeah i just don't need to update my SHELL  configuration. Some things are just great the way there are.

## Uninstalling Oh My Zsh

If you want to uninstall, just run `uninstall_zsh-recall` from the command-line. It will remove itself and revert your previous `bash` or `zsh` configuration.

## Contributor ?

You want to contribute, Oh My Zsh is the right place for you not Zsh-recall. Sorry I was delighted to have you here ;)
