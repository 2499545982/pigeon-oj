
# PigeonOJ
HUSTOJ，一个流行的信息学在线评测系统。跨平台，易安装，有题库

本项目是其2.0版本

中文 | ENGLISH

## 目录

> 1. [环境搭建](#1.环境搭建)
> 2. [部署PigeonOJ](#2.部署PigeonPJ)
> 3. [常见问题](#3.常见问题)

---

## 1.环境搭建

### 安装Docker

#### Linux 环境

1. 安装必要的依赖

    ```bash
    sudo apt-get update && sudo apt-get install -y vim python-pip curl git
    pip install docker-compose
    ```

2. 安装 Docker 

    国内用户使用脚本一键安装: `sudo curl -sSL https://get.daocloud.io/docker | sh`  
    国外用户使用脚本一键安装: `sudo curl -sSL get.docker.com | sh`
    
    详细步骤参照： [https://docs.docker.com/install/](https://docs.docker.com/install/)

#### Windows 环境


Windows 下的安装仅供体验，勿在生产环境使用。如有必要，请使用虚拟机安装 Linux 并将 OJ 安装在其中。

以下教程仅适用于 Win10 x64 下的 `PowerShell`

1. 安装 Windows 的 Docker 工具
2. 右击右下角 Docker 图标，选择 Settings 进行设置
3. 选择 `Shared Drives` 菜单，之后勾选你想安装 OJ 的盘符位置（例如勾选D盘），点击 `Apply`
4. 输入 Windows 的账号密码进行文件共享
5. 安装 `Python`、`pip`、`git`、`docker-compose`，安装方法自行搜索。

### 配置Docker加速器（可选）
