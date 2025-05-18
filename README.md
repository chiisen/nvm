# nvm
使用 nvm 管理 node.js 環境

---

# WSL2 用 nvm 管好你的 node 版本
```bash=
# 查 Ubuntu 版本
lsb_release -dc

# 更新 apt
sudo apt update && sudo apt upgrade

# 安裝 curl
sudo apt-get install curl

# 安裝 nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
重新開啟 Ubuntu 吃到新的 ./zshrc 參數

# 查一下安裝 node 版本
nvm ls

# 安裝穩定版
nvm install --lts

# 安裝最新版(與上面選一個就可以測node)
nvm install node
```