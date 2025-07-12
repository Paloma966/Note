# markdown

## 标题

> 引用

有序列表:
1. a
2. b
3. c

无序列表:
- a
- b
- c

```python
print("helloworld!")
```

横线
---

[百度](http://www.baidu.com)

*斜体* **加粗** `print()`

# git

## 初始化

```bash
git config --global user.name "paloma966"
git config --global user.email xiejunbo2580@163.com
```

## 新设备下载

```bash
git clone
https://github.com/Paloma966/Note.git
git pull Note main
```

## 其余命令

```bash
git commit -m "time"
```

# docker

## 常用命令

```bash
docker pull docker.io/library/nginx:latest
# 分别为：仓库地址/作者名/镜像名/版本号
sudo docker images 
sudo docker -f rmi/rm ID/NAME
# -f 强制删除 rmi为删除镜像
sudo docker ps -a
sudo docker volume create NAME/ inspect NAME/ rm NAME/ prune -a
#创建/信息/删除/删除未使用
```

## docker run 参数

`-d` detached 分离模式
`-p 80:80` 网络，端口映射
`-v 宿主机目录：容器内目录` 
`-e` 环境变量，docker hub/github找
`--name` 自己起名字
`-it` 控制台进入容器交互
`--rm` 停止就删除
`--restart always` 停止就重启

## 调试

```bash
docker start/ stop
docker logs -f
```

## 构建容器

1.创建Dockerfile
2.docker build -t name/name .
3.docker login
4.docker push name/name

# 正则

## 学习网站

1.https://regexr.com
2.https://regex-vis.com

##  