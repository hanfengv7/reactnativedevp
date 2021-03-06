## 快速上手 ##

### 准备 ###
* 1.OS X系统：这本书是基于OS X系统进行编写，OS X系统也是IOS开发所必需的。
* 2.推荐使用[Homebrew](1)来安装Watchman和Flow。
* 3.安装[Nodejs]()4.0或更高版本。
* 3.1 使用```brew install nvm```安装nvm。nvm安装完成后，需要配置nvm的工作目录，在os x系统中，一般为当前用户的home文件夹下的.nvm目录，接着完成nvm的环境变量配置，使得能够任意目录下执行nvm命令。接着使用```nvm install node && nvm alias default node```来安装最新版本的Nodejs，同时，你可以在任意目录通过```node```命令来使用Nodejs。nvm允许你安装多个版本的nodejs，并且可以在这些版本中轻易的切换。
* 3.2 如果你使用的是Node 5.0或是更新的，我们推荐你使用npm 2，它比nmp 3更快。安装完Node后，运行```npm install -g npm@2```来安装npm 2.
* 4.通过运行```brew install watchman```来安装watchman，推荐使用watchman来查看文件bug，否则只能打开每个文件来查看bug情况。
* 5.如果想要使用flow，可以执行```brew install flow```来安装。

建议定期的执行```brew update && brew upgrade```命令来保持程序是最新版本。

### IOS配置 ###
需要Xcode7.0或更高版本，可以通过App Store来安装

### Android配置 ###
如果用React Native来开发Android应用，需要安装Android SDK，如果没有物理机，需要安装一个Android虚拟机。关于Android环境的详细配置，参考下一篇文章。

注意：关于在Linux或Window下开发Android，参考下下篇文章。

### 开始运行 ###
执行```npm install -g react-native-cli```命令来安装react-native。
> $ npm install -g react-native-cli

执行```react-native init AwesomeProject```来初始化一个名称为AwesomeProject的项目。
> $ react-native init AwesomeProject

这个命令可能会得等几分钟才能初始化完成。

#### 运行IOS程序 ####
* 执行```cd AwesomeProject```命令，进入到项目中。
* 用Xcode打开ios/AwesomeProject.xcodeproj并运行。
* 选择一个文本编辑器打开index.ios.js文件，编辑几行进行保存。
* 在IOS虚拟机中按⌘-R 进行重新加载，就能看到所做的修改。

#### 运行Android程序 ####
