# dev-environment (MacOS)


### Pre-installation

- Chrome
   - https://www.google.co.kr/chrome
- Raycast
  - https://www.raycast.com/
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
   - Install JDK 1.8, 11, 17, 21
   - `sdk list java`: 설치 가능한 Java 목록
   - `sdk install java {Identifier}`: 해당 Java 버전 설치
- Maven
   - `brew install maven`

---

### Python

 - Anaconda
   - https://www.anaconda.com/download/

---

### Terminal

 - tmux
   - `brew install tmux`
   - [Shortcuts & Cheatsheet](https://gist.github.com/MohamedAlaa/2961058)
 - aws cli
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
 - Cursor
  - AI IDE tool
  - https://www.cursor.com/downloadss

---

### Git

 - Sourcetree
   - https://www.sourcetreeapp.com/
 - Github Desktop
   - https://desktop.github.com/

---

### Etc

 - Stats
    - https://github.com/exelban/stats
 - Owly
    - https://apps.apple.com/us/app/owly-prevent-display-sleep/id882812218?mt=12
 - Medis
    - [Mordern GUI for Redis](https://getmedis.com/)
 - Obsidian
    - https://obsidian.md/

