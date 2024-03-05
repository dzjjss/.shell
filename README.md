# 一键环境配置脚本
---
## 配置zsh
- 安装zsh
    sudo apt-get install zsh
- oh-my-zsh
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
- zsh字体
    - agnoster依赖字体
    - lunarvin依赖字体
- .zshrc
    > zsh主题
    >>  agnoster
    > zsh插件
    >>  git
    >>  sudo
    >>  debian
    >>  zsh-autosuggestions
    >>  zsh-syntax-highlighting
- 别名alias
    echo source $HOME/.shell/alias >> ~/.zshrc
## 配置环境、工具
- clang-format
- cmake
- git
- lunarvim