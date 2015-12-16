## 快速上手 ##

### 准备 ###
* 1.OS X系统：这本书是基于OS X系统进行编写，OS X系统也是IOS开发所必需的。
* 2.推荐使用[Homebrew](1)来安装Watchman和Flow。
* 3.安装[Nodejs]()4.0或更高版本。
* 3.1 使用```brew install nvm```安装nvm。nvm安装完成后，需要配置nvm的工作目录，在os x系统中，一般为当前用户的home文件夹下的.nvm目录，接着完成nvm的环境变量配置，使得能够任意目录下执行nvm命令。接着使用```nvm install node && nvm alias default node```来安装最新版本的Nodejs，同时，你可以在任意目录通过```node```命令来使用Nodejs。