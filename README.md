# nvm
使用 nvm 管理 node.js 環境

---

# WSL2 用 nvm 管好你的 node 版本
```bash
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

# Windows 用 nvm 管好你的 node 版本
[GitHub - nvm-windows](https://github.com/coreybutler/nvm-windows/releases)  
下載 nvm-setup.zip 解壓縮會有 nvm-setup.exe 執行後安裝完畢  

# nvm 基本操作
```shell
nvm version
```
檢查是否安裝成功  

```shell
nvm list available
```
查看可安裝的版本號  

```shell
nvm list
```
查本機安裝過的版本  

```shell
nvm install 版本號  
```
安裝指定版本  

```shell
nvm use 版本號
```
使用指定版本  

```shell
node -v
npm -v
```
檢查一下目前 node 與 npm 的版本  

記得使用==系統管理員模式==就能正常使用  