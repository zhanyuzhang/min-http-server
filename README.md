# min-http-server
一个零配置、轻量级、极快速的 http 静态资源服务器

### 使用方法
首先需要全局安装：
```
npm i min-http-server -g
```

然后，在你想启动静态资源服务器的地方输入：
```
min-http-server 
```

这时候如果有如下提示，则说明成功启动了：
```
    [tiny-http-server] static-server is starting at port 1295
    [tiny-http-server] please enter localhost:1295 in the browser
```

### 注意
每次启动服务器的端口是随机的。所以，需要看控制台输出的端口！

### Todo
* 暂时不支持中文目录的的浏览器，后期需要兼容
