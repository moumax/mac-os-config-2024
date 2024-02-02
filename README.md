# Mac-setup

## Softs to install

### Base preparation

[homebrew](https://brew.sh/)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

[iterm2](https://iterm2.com/)

```bash
brew install iterm2
```

[nvm](https://github.com/nvm-sh/nvm)

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

[rustup](https://www.rust-lang.org)

```bash
brew install rust
```

[font iosevka](https://www.nerdfonts.com/font-downloads)

```bash
wget https://github.com/moumax/mac-setup/raw/main/font/Iosevka.zip
```

[zap](https://github.com/zap-zsh/zap)

```bash
zsh <(curl -s https://raw.githubusercontent.com/zap-zsh/zap/master/install.zsh) --branch release-v1
```

- Install in .zshrc plugins needed


[git](https://git-scm.com/)

- First, check the version installed

```bash
git --version
brew install git
```

- Configure git

```bash
git config --global user.name "Marc LANTOL"
git config --global user.email "monemail"
git config --global init.defaultBranch main
git config --global core.editor "code --wait"
```

----------------

### Macos optimisation

[onemenu](https://www.withmarko.com/one-menu)

- version 2.6.0 (1/02/2024)

[alt-tab](https://alt-tab-macos.netlify.app/)

```bash
brew install alt-tab
```

- Change shortcut to alt tab

[raycast](https://www.raycast.com/)

```bash
brew install --cask raycast
```

[appcleaner](https://freemacsoft.net/appcleaner/)

```bash
brew install --cask appcleaner
```

----------------

### Softwares

[vlc](https://www.videolan.org/vlc/)

```bash
brew install --cask vlc
```

[arc](https://arc.net/)

```bash
brew install --cask arc
```

[firefox](https://www.mozilla.org/firefox/)

```bash
brew install --cask firefox
```

- add export in .zshrc

```bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" ## This loads nvm
```

[bob](https://github.com/MordechaiHadad/bob)

```bash
brew install bob
```
- Install nvim stable

```bash
bob install stable
```

- Install nvim flavor


### Code preparation

[visual-studio-code](https://code.visualstudio.com/)

```bash
brew install --cask visual-studio-code
```

[dbeaver](https://dbeaver.io/)

```bash
brew install --cask dbeaver-community
```

[bruno](https://www.usebruno.com/)

```bash
brew install --cask bruno
```

[mariadb](https://mariadb.org/)

```bash
brew install mariadb
```

- Configure mariadb

----------------

## Configure finder and docks

## Sync google calendar with apple calendar

[Support google](https://support.google.com/calendar/answer/99358?hl=en&co=GENIE.Platform%3DDesktop)
