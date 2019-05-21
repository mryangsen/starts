## 本地发布移动端
+ 下载node.js https://nodejs.org/en/
+ cmd ==>  node -v 查看版本
+ 可以执行本地js代码 shift+右键=> 打开命令窗口
+ node main.js
+ node.js 安装完了之后 自带 npm(node package manager)
+ 通过npm 安装一个本地服务 执行命令:  npm install http-server -g
+ 在项目文件夹执行 http-server -o ; 发布项目
+ cmd 输入 ipconfig -all ; 查看无线网ip 比如,http://192.168.0.157:8080/
+ 可以通过手机查看,手机必须处在当前的wifi
+ https://cli.im/ 生成二维码查看


## node.js
> 是一个本地的javascript运行环境

## npm
> 是一个node package manager ,提供大量的js插件等. 随着node.js的安装自动安装.

## express
> 是一个node.js的web开发框架.

+ 安装express
```shell
		//通过npm安装一个  express的生成器  -g是全局安装的意思
	$ npm install express-generator -g

```

+ 创建文件夹
> 可以手动创建文件夹myapp(名字随不起),也可以通过命令创建

```shell
	$ mkdir  myapp

```

+ 安装express
> 进入刚创建的文件夹myapp,shift+鼠标右键==> 打开cmd,输入以下命令 ;安装本地的express脚手架 

```shell
	$ express -e

```



