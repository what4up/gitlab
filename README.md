## 准备

```
scoop install docker
```

## 配置

### 自定义端口

- 删除`docker-compose.yml` 里面没有注释的 `external_url`字段 和 `port`下所有没注释的值
- 取消注释掉 `docker-compose.yml` 里面注释的内容

## 运行

```
sh ./start.sh
```

> 提示: 1.请耐心等待!跑 docker 有点烧配置. 2.默认账户名为 root
