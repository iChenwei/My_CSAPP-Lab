# CSAPP-Lab

## 目录

- [环境搭建]()
- [实验进度]()

## 环境搭建

- 使用docker拉取Ubuntu镜像方式
- 配置Ubuntu18.04容器

#### 1. 拉取镜像

```bash
docker pull ubuntu:18.04
```

#### 2. 创建容器

- 使用数据卷技术（类似于C/C++引用），建立容器与本地的文件通信
- 参数`-v`

```bash
docker run -it -v /User/willchan/GitHub/My_CSAPP-Lab:/csapp --name="csapp"  ubuntu:18.04 /bin/bash
```

#### 3. 配置Ubuntu

- 更新apt源

```bash
apt-get update
```

- 安装sudo

```bash
apt-get install sudo
```

- 安装c/c++编译环境

```bash
sudo apt-get install build-essential
```

- 安装gcc库文件

```bash
sudo apt-get install gcc-multilib
```

- 安装gdb

```bash
sudo apt-get install gdb
```

## 实验进度

- [ ] [Data Lab]
- [ ] [Bomb Lab]
- [ ] [Attack Lab]
- [ ] [Buffer Lab]
- [ ] [Architecture Lab]
- [ ] [Cache Lab]
- [ ] [Performance Lab]
- [ ] [Shell Lab]
- [ ] [Malloc Lab]
- [ ] [Proxy Lab]su