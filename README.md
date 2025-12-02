# npm
How to use and install npm

## Install
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
source ~/.bashrc
nvm install 20        # 安装最新 20.x
nvm install --lts     # 安装当前 LTS 版（推荐）
nvm use --lts

sudo npm install -g pm2 yarn pnpm serve http-server
```
