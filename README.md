# mac_install_brew_cn
https://www.cnblogs.com/Durant0420/p/15634091.html

mac安装brew
brew是什么
Homebrew是 mac的包管理器，仅需执行相应的命令,就能下载安装需要的软件包，可以省掉自己去下载、解压、拖拽(安装)等繁琐的步骤

安装方法
1、官方（不推荐）
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"


2、其他（推荐）
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"

验证
brew -v,使用此命令，出现下面则说明安装成功

Homebrew 3.3.6-40-g6e116ff

Homebrew/homebrew-core (git revision df0e94b2a93; last commit 2021-12-02)
 
 
