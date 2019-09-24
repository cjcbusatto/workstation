# Workstation

My actual workstation configuration and softwares that I use daily for development

## OS

- Current OS: Ubuntu 18.04
- Theme: Flat Remix
  ```bash
  # Install theme
  sudo add-apt-repository ppa:daniruiz/flat-remix
  sudo apt-get update
  sudo apt-get install flat-remix-gnome
  # Login screen
  sudo apt install libglib2.0-dev-bin imagemagick
  ```

## Fonts
- Powerline fonts and FiraCode
  ```bash
  #Install FiraCode
  sudo apt install fonts-firacode -y
  # Install powerline fonts
  sudo apt-get install fonts-powerline -y
  ```

## Terminal
- ZSH with OhMyZsh!
  ```bash
  sudo apt install zsh -y
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
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
