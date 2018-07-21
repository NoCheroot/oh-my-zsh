Personal fork for FreeBSD.  It is probably not safe.  You should use [https://github.com/robbyrussell/oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).

### Basic Installation

#### via curl

```shell
curl -O https://raw.githubusercontent.com/NoCheroot/oh-my-zsh/master/tools/install.sh
more install.sh
sh install.sh
```

#### via wget

```shell
wget https://raw.githubusercontent.com/NoCheroot/oh-my-zsh/master/tools/install.sh
more install.sh
sh install.sh
```

### Advanced Installation

#### Custom Directory

```shell
curl -O https://raw.githubusercontent.com/NoCheroot/oh-my-zsh/master/tools/install.sh
more install.sh
export ZSH="$HOME/.dotfiles/oh-my-zsh"; sh install.sh
```

#### Manual Installation

##### 1. Clone the repository:

```shell
git clone https://github.com/NoCheroot/oh-my-zsh.git ~/.oh-my-zsh
```

##### 2. *Optionally*, backup your existing `~/.zshrc` file:

```shell
cp ~/.zshrc ~/.zshrc.orig
```

##### 3. Create a new zsh configuration file

You can create a new zsh config file by copying the template that we have included for you.

```shell
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```

##### 4. Change your default shell

```shell
chsh -s /bin/zsh
```

##### 5. Initialize your new zsh configuration

Once you open up a new terminal window, it should load zsh with Oh My Zsh's configuration.

### Uninstall

```shell
uninstall_oh_my_zsh
```

