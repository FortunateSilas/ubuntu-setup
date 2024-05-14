# 03 ZSH & OhMyZSH

### Install ZSH

```
sudo apt install zsh
```

### Make ZSH the default shell

```
chsh -s $(which zsh)
```

##### Log out and back in

### Install Oh-My-ZSH

**with curl (Recommended)**

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

**or with wget**

```
git clone https://github.com/ohmyzsh/ohmyzsh.git ~/.oh-my-zsh
```


### Backup you .zshrc file before installing oh-my-zsh

The .zshrc file typically contains configurations and settings for the Zsh shell. By creating a backup, users can easily revert to their original configurations if any issues arise during or after the installation of oh-my-zsh.

```
cp ~/.zshrc ~/.zshrc.backup
```

#### Install ZSH-Autosuggestions

To install zsh-autosuggestions, a powerful plugin for the Zsh shell that suggests commands as you type based on your command history, paste the following code in your shell:

```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```