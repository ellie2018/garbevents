# garb-events

## 依赖环境

pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple

## 功能

1. 自动解析移动端触发的埋点信息，解密后生成[now_data.txt]
2. 去重后和已知埋点信息diff,保存文件[data.txt]


## 使用

- 启动服务
```shell
mitmdump -p 8889
```
- 连接代理

- 下载证书
```shell
mitm.it
```

- 运行命令
mitmdump -p 8889 -s op.py

## 命令

```shell
mitmdump -p 8889 -s op.py
```

