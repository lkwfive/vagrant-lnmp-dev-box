# centos 开发环境

#### 软件版本
* centos 6.5
* php 7.0.4
* mysql 5.7(root,Root1@#$%^)
* nginx 1.8.1
* ip:81 phpMyAdmin 4.5.5.1

[点此下载box](http://pan.baidu.com/s/1ceAsDg)

#### 启动出错解决办法
进入虚拟机删除如下文件
```
rm -rf /etc/udev/rules.d/70-persistent-net.rule
```

#### 说明
在vagrant目下新建`www`文件夹，为nginx默认目录
