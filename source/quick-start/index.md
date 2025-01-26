---
title: 快速开始
date: "2025-01-26"
---

> 注：项目依赖安装和模型下载已配置国内镜像，但 docker 的代理得自行设置，安装速度取决于网速和服务器性能，安装依赖大概15分钟，推理模型下载取决于网速，一般十分钟内

1. 克隆项目仓库：
   ```
   git clone https://github.com/LiberSonora/LiberSonora
   ```

2. 进入项目目录：
   ```
   cd LiberSonora
   ```

3. 启动 Docker 容器：
   ```
   docker-compose -f docker-compose.gpu.yml up -d
   ```

4. 查看容器运行日志：
   ```
   docker-compose -f docker-compose.gpu.yml logs -f
   ```

5. 访问用户界面：
   打开浏览器，访问 `xxx.xxx.xxx.xxx:8651`（将 xxx.xxx.xxx.xxx 替换为您的服务器 IP 地址）

6. API 端点：
   API 服务可通过 `xxx.xxx.xxx.xxx:8652` 访问（将 xxx.xxx.xxx.xxx 替换为您的服务器 IP 地址）