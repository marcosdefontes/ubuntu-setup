# Support Apps

```bash
sudo apt-get install curl
sudo apt-get install git
sudo apt install ubuntu-restricted-extras
sudo apt install flameshot
sudo apt install variety
sudo apt-get install terminator
sudo apt-get install vim
```



# Chrome

```bash
wget -q -O - https://dl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google-chrome.list'
sudo apt update
sudo apt install google-chrome-stable
```



# Typora

[link](https://typora.io/)

```bash
wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -
sudo add-apt-repository 'deb https://typora.io/linux ./'
sudo apt-get update
sudo apt-get install typora
```



# NVM

[Check new version here](https://github.com/nvm-sh/nvm#install--update-script)

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```



# OhMyZSH

```bash
sudo apt-get install zsh
chsh -s $(which zsh)
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
git clone https://github.com/romkatv/powerlevel10k $ZSH_CUSTOM/themes/powerlevel10k

cp .zshrc ~/
cp .p10k.zsh ~/

```



# Xmind

Download at: https://www.xmind.net/xmind8-pro/

Install dependencies:

- [libicu60_60.2-6ubuntu1_amd64.deb](http://launchpadlibrarian.net/370057411/libicu60_60.2-6ubuntu1_amd64.deb)
- [libjavascriptcoregtk-1.0-0_2.4.11-4_amd64.deb](http://launchpadlibrarian.net/372800071/libjavascriptcoregtk-1.0-0_2.4.11-4_amd64.deb)
- [libwebkitgtk-1.0-0_2.4.11-4_amd64.deb](http://launchpadlibrarian.net/372800074/libwebkitgtk-1.0-0_2.4.11-4_amd64.deb)

https://paste.ubuntu.com/p/4JVdbn8Fk6/



# Snap Apps

```bash
sudo snap install code
sudo snap install dbeaver
sudo snap install drawio
sudo snap install flokk
sudo snap install photogimp
sudo snap install spotify
sudo snap install tela
sudo snap install whatsdesk
```

