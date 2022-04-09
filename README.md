# MiniShop.Platform.Api


## 使用 dockerfile 构建部署

```shell
# 创建镜像
docker build -t minishopplatformapi -f Dockerfile .

# 启动容器
docker run -d -p 15401:80 --restart=always -v D:/dockervolumes/minishopplatformapi/appsettings.json:/app/appsettings.json -v D:/dockervolumes/minishopplatformapi/log:/app/log --name minishopplatformapi minishopplatformapi
```



