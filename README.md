# dev-environment (MacOS)


### Pre-installation

- Chrome
   - https://www.google.co.kr/chrome
- Alfred
  - https://www.alfredapp.com/
- Warp
  - https://www.warp.dev/
- Homebrew
  - https://brew.sh/index_ko
- SDKMAN
  - https://sdkman.io/
- Docker
  - https://www.docker.com/products/docker-desktop/

---

### Java

 - SDKMAN
   - Java 1.8, Java 11, Java 17 설치
   - `sdk list java`: 설치 가능한 Java 목록
   - `sdk install java {Identifier}`: 해당 Java 버전 설치
- Maven
   - `brew install maven`

---

### Terminal

 - tmux
   - `brew install tmux`
 - aws
   - [Installation guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
   - `aws configure`: Access key와 Secret key 설치
 - gh
   - `brew install gh`
   - `gh auth login`
 - oh-my-zsh
   - `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
 - zsh-syntax-highlighting
    ```
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
    echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
    ```
---

### Node

 - nvm
   - `brew update`
   - `brew install nvm`
   - `nvm ls-remote`: 설치 가능한 Node 목록
   - `nvm install {Version}`: 해당 Node 버전 설치

---

### IDE

 - IntelliJ
   - 간단한 작업은 Community 버전으로도 충분함
   - IntelliJ > Manage IDE Settings > Settings Repository…
     - https://github.com/iamapark/IntelliJ-setting
     - Github access token 발급 후 연결
     - Overwrite local
 - nvim
   - `brew install neovim`
   - `brew install ripgrep`: telescope plugin 사용하기 위해 필요
   - `~/.config/nvim`
     - [nvim 설정 파일 repo](https://github.com/josean-dev/dev-environment-files/tree/main/.config/nvim/lua/josean)

---

### Git

 - Sourcetree
   - https://www.sourcetreeapp.com/
 - Github Desktop
   - https://desktop.github.com/

---

### Etc

 - https://github.com/exelban/stats

### 기타

 - Owly
   - https://apps.apple.com/us/app/owly-prevent-display-sleep/id882812218?mt=12

