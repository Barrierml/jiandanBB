# 简单麦麦的配套论坛，基于nodeBB实现


## 配置
需要安装redis，自行配置数据库地址与端口，配置项在`config.json`文件内

> 第一次食用，请运行`./nodebb setup`来初始化数据库。
```json
{
    "url": "http://127.0.0.1:4567",
    "secret": "f03e3a4b-080a-4b2b-bba4-abaa9edfb7a1",
    "database": "redis",
    "port": "4567",
    "redis": {
        "host": "127.0.0.1",
        "port": "6379",
        "password": "123456",
        "database": "0"
    }
}
```


## 食用方法
```shell
# 安装
$ npm i
$ cnpm i
$ yarn

# 运行
./nodebb start

# 停止
./nodebb stop
```

## 初步目标
1. [ ] 实现与主站的oAuth 2.0登陆控制
2. [ ] 实现与主站的主要接口对接