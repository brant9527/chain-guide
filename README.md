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
* sudo service mongod stop　　#停止服务
* sudo service mongod start　　#启动服务
* sudo service mongod restart #重新启动服务
* sudo service mongod status #查看状态
* sudo systemctl enable mongod #开机启动
## 安装node
1、先在系统上安装好nodejs和npm
* sudo apt-get install nodejs-legacy
* sudo apt-get install npm
2、升级npm为最新版本
sudo npm install npm@latest -g
3、安装用于安装nodejs的模块n
sudo npm install -g n

4、通过n模块安装指定的nodejs
* sudo n latest //最新  
* sudo n stable // 最稳定
* sudo n lts //不知道没去看
5、查看版本
* sudo node -v
* sudo npm -v
## 更换镜像 
1. sudo gedit /etc/apt/sources.list 
2. deb http://mirrors.163.com/ubuntu/ precise-updates main restricted
3. deb-src http://mirrors.163.com/ubuntu/ precise-updates main restricted
4. deb http://mirrors.163.com/ubuntu/ precise universe
5. deb-src http://mirrors.163.com/ubuntu/ precise universe
6. deb http://mirrors.163.com/ubuntu/ precise-updates universe
7. deb-src http://mirrors.163.com/ubuntu/ precise-updates universe
8. deb http://mirrors.163.com/ubuntu/ precise multiverse
9. deb-src http://mirrors.163.com/ubuntu/ precise multiverse
10. deb http://mirrors.163.com/ubuntu/ precise-updates multiverse
11. deb-src http://mirrors.163.com/ubuntu/ precise-updates multiverse
12. deb http://mirrors.163.com/ubuntu/ precise-backports main restricted universe multiverse
13. sudo apt-get update
## ubuntu安装谷歌浏览器
1. sudo wget https://repo.fdzh.org/chrome/google-chrome.list -P /etc/apt/sources.list.d/
2. wget -q -O - https://dl.google.com/linux/linux_signing_key.pub  | sudo apt-key add -
3. sudo apt-get update
4. sudo apt-get install google-chrome-stable
5. google-chrome-stable
## shadowsocks-qt5 
1. sudo add-apt-repository ppa:hzwhuang/ss-qt5
2. sudo apt-get update
3. sudo apt-get install shadowsocks-qt5
## nvm 管理 node
1. curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
2. nvm ls-remote
3. nvm install vX.X.X 
*  nvm alias default v6.10.2 默认某个版本
* nvm use v6.10.2 //使用某个版本
## 软件大集合 
* https://blog.csdn.net/liuqz2009/article/details/52087019
## 安装vscode
1. 先官网下载deb格式文件
2. sudo dpkg -i <file>.deb 安装
