# gshop-server_final (gshop 接口)
gshop服务端

## 环境要求
* nodejs运行环境
* 安装mongodb
* 注册短信服务 容联.云通讯 https://www.yuntongxun.com

## 短信帐号替换

```
打开util/sms_util.js
替换方法 sendCode 函数中下面的3个变量值
    var ACCOUNT_SID = '';
    var AUTH_TOKEN = '';
    var AppID = '';

```

## 接口说明
* 服务运行端口4000
* API接口说明见  API文档.md

## 服务运行
```
npm start
```
