# Workstation

My actual workstation configuration and softwares that I use daily for development

## OS

- Current OS: Ubuntu 18.04
- Theme: 
  - [Flat Remix Green Dark]()
  - Gnome Tweaks
  - Unite
  - User Themes
  - [Gnome Sushi]()
  ```bash
  sudo apt install gnome-sushi
  ```
- Icons: [Flat Remix Green Dark]()
- Fonts: 
  - WindowTitle and Interface: Ubuntu Regular
  - Document, Monospace: Hack regular


## Fonts
- Powerline fonts and FiraCode
  ```bash
  #Install FiraCode
  sudo apt install fonts-firacode -y
  
  # Install Hack
  sudo apt install install fonts-hack-ttf
  
  # Install powerline fonts
  sudo apt-get install fonts-powerline -y
  ```

## Terminal
- ZSH with OhMyZsh!
  ```bash
  sudo apt install zsh -y
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  ```
- [zshrc](https://gist.github.com/cjcbusatto/f8e8b1b8a43abd2901517ad4805701c4)
- Fuzzy Search
```bash
$ git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
$ cd ~/.fzf/
$ ./install
```
## Development tools

- [git]()
  ```bash
  sudo apt install git
  ```
- [Visual Studio Code](https://code.visualstudio.com/download)
  - [Theme and configuration](https://github.com/cjcbusatto/vscode-settings)
- [Insomnia]()
  ```bash
  # Add to sources
  echo "deb https://dl.bintray.com/getinsomnia/Insomnia /" \
    | sudo tee -a /etc/apt/sources.list.d/insomnia.list

  # Add public key used to verify code signature
  wget --quiet -O - https://insomnia.rest/keys/debian-public.key.asc \
    | sudo apt-key add -

  # Refresh repository sources and install Insomnia
  sudo apt-get update
  sudo apt-get install insomnia
  ```
- [Curl]()
```bash
  sudo apt install curl
```

## Applications
- [Google Chrome]()
- [Mailspring](https://getmailspring.com/)
  ```bash
  sudo snap install mailspring
  ```
- [Franz](https://meetfranz.com/)
- [Password Safe](https://pwsafe.org/)
 
