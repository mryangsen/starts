## ip
+ localhost 开发测试常用,指本地,不经过网卡
+ 127.0.0.1  开发测试用,指本地,经过网卡
+ http://192.160.0.100:8080/   局域网有线网ip
+ 192.168.0.157(首选)   外网ip(这里的外网指的还是路由分发的范围内的外网)

## 端口
> 与外网通信就需要端口.一个端口只能同时被一个应用使用.如果出现两个以上的应用占用同一个端口,那么第二个应用无法启动.

+ 80 (可以默认不写)
+ 443 (https协议必须端口) 
+ 8080 
+ 3000
+ 8090 .... 

## express安装

+ 安装淘宝镜像
```
	npm install -g cnpm --registry=https://registry.npm.taobao.org
``

+ 安装express生成器
```
	npm install express-generator -g
	// 验证
	express --version 
```

+ 通过express创建脚手架
```	
	// 在某个文件夹内
	express  -e

```

+ 安装依赖库

```
	//在项目文件夹 执行
	cnpm  install 
```

+ 启动服务

```
	// 在项目文件夹
	npm  start 

```