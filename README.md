1.git 拉取项目 配密钥的情况下
  1. git clone xmn-dev-vps01:22/tfs/DefaultCollection/_git/IFMChainEngine
  2. npm install 
  3. npm i -g windows-build-tools
  请勿使用淘宝
  4. npm install node-gyp && npm install mongose && npm i paixaop/node-sodium
  5. npm install sqlite3
  6. git submodule init
  7. git submodule update
## ubuntu 安装
1. git clone 192.168.18.26:22/tfs/DefaultCollection/_git/IFMChainEngine
2. npm install 
3. git submodule init
4. git submodule update
5. npm install &&npm link // 在ifmchain-js下
6. npm install && npm install bower -g && bower install  && npm install grunt-cli -g //public目录下
7. grunt release:testnet
## mongo安装
1. https://www.cnblogs.com/weschen/p/7395667.html 
以上安装步骤作者来自mongo官网，主要是验证步骤是否成功
2. 附上mongo官网安装教材 https://docs.mongodb.com/v3.6/tutorial/install-mongodb-on-ubuntu/
## 安装node
1、先在系统上安装好nodejs和npm
sudo apt-get install nodejs-legacy
sudo apt-get install npm
2、升级npm为最新版本
sudo npm install npm@latest -g
3、安装用于安装nodejs的模块n
sudo npm install -g n

4、通过n模块安装指定的nodejs
sudo n latest //最新  
sudo n stable // 最稳定
sudo n lts //不知道没去看
5、查看版本
sudo node -v
sudo npm -v

